+++
title = "Contact"
slug = "contact"
+++

<style>
#contact-form {
    border: 2px solid var(--border-color);
    border-radius: 8px;
    padding: 20px;
    max-width: 600px;
    margin: 0 auto;
}

#contact-form input,
#contact-form textarea {
    width: 100%;
    padding: 10px;
    margin-top: 5px;
    margin-bottom: 15px;
    border-radius: 4px;
}

#contact-form button {
    border-radius: 4px;
    padding: 10px 20px;
    cursor: pointer;
}
</style>

<form id="contact-form" method="POST">
    <label for="name">Name</label>
    <input type="text" id="name" name="entry.319816423" required />
    <label for="email">Email</label>
    <input type="email" id="email" name="entry.16391762" required />
    <label for="message">Message</label>
    <textarea id="message" name="entry.759063854" rows="5" required></textarea>
    <button type="submit" value="Submit">Send Message</button>
</form>

<script>
document.getElementById('contact-form').addEventListener('submit', function(event) {
    event.preventDefault();

    const form = this;
    const formData = new FormData(form);
    const url = "https://docs.google.com/forms/d/e/1FAIpQLScwzjnhWHynBxwPjmTlGBz3r5BGrovzJyQT38CjnJyuC_kLhQ/formResponse";
    fetch(url, {
        method: "POST",
        body: formData,
        mode: "no-cors"
    })
    .then(() => {
        form.innerHTML = `
            <p>Thank you for your message! I will get back to you soon.</p>
        `;
    })
    .catch((error) => alert('Error submitting form. Please try again.'));
});
</script>
