# yourshoppingcenter.github.io
My shopping center website 
<!-- Contact / Order Form Section -->
<section id="contact" style="max-width:700px; margin:50px auto; padding:30px; border:1px solid #ddd; border-radius:10px; background-color:#f9f9f9; font-family:Arial, sans-serif; box-shadow:0 4px 8px rgba(0,0,0,0.1);">
  <h2 style="text-align:center; color:#333; margin-bottom:10px;">Contact Carti World</h2>
  <p style="text-align:center; color:#555; margin-bottom:30px;">Send us a message or order inquiry and we will get back to you!</p>

  <form action="https://formspree.io/f/xxxxxx" method="POST" style="display:flex; flex-direction:column; gap:20px;">
    <label for="name" style="font-weight:bold; color:#333;">Your Name:</label>
    <input type="text" name="name" placeholder="John Doe" required style="padding:12px; border-radius:6px; border:1px solid #ccc; font-size:16px;">

    <label for="email" style="font-weight:bold; color:#333;">Email Address:</label>
    <input type="email" name="email" placeholder="johndoe@example.com" required style="padding:12px; border-radius:6px; border:1px solid #ccc; font-size:16px;">

    <label for="message" style="font-weight:bold; color:#333;">Message / Order Details:</label>
    <textarea name="message" placeholder="Write your message or order details here..." required style="padding:12px; border-radius:6px; border:1px solid #ccc; font-size:16px; min-height:120px;"></textarea>

    <button type="submit" style="padding:14px; background-color:#ff6600; color:white; border:none; border-radius:6px; font-size:16px; font-weight:bold; cursor:pointer; transition: background-color 0.3s;">
      Send Message
    </button>
  </form>

  <script>
    // Simple hover effect for the button
    const button = document.querySelector('button[type="submit"]');
    button.addEventListener('mouseover', () => button.style.backgroundColor = '#e65c00');
    button.addEventListener('mouseout', () => button.style.backgroundColor = '#ff6600');
  </script>
</section>
