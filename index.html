// Cart functionality
let cart = [];
let cartCount = 0;

function addToCart(button) {
    const productCard = button.closest('.product-card');
    const productData = JSON.parse(productCard.dataset.product);
    
    cart.push(productData);
    cartCount++;
    updateCartUI();
    
    // Visual feedback
    button.textContent = 'Added!';
    setTimeout(() => { button.textContent = 'Add to Cart'; }, 1000);
}

function updateCartUI() {
    document.getElementById('cart-count').textContent = cartCount;
    document.getElementById('cart-total-items').textContent = cartCount;
    
    const cartItems = document.getElementById('cart-items');
    cartItems.innerHTML = '';
    let total = 0;
    
    cart.forEach((item, index) => {
        const cartItem = document.createElement('div');
        cartItem.classList.add('cart-item');
        cartItem.innerHTML = `
            <span>${item.name} - ${item.price}</span>
            <button onclick="removeFromCart(${index})">Remove</button>
        `;
        cartItems.appendChild(cartItem);
        total += parseInt(item.price.replace('$', '').replace(',', ''));
    });
    
    document.getElementById('cart-total').textContent = `Total: $${total.toLocaleString()}`;
}

function removeFromCart(index) {
    cart.splice(index, 1);
    cartCount--;
    updateCartUI();
}

function toggleCart() {
    const sidebar = document.getElementById('cart-sidebar');
    sidebar.classList.toggle('hidden');
}

function checkout() {
    if (cart.length === 0) {
        alert('Your cart is empty!');
        return;
    }
    alert('Proceeding to checkout... (Integrate with payment gateway here)');
    cart = [];
    cartCount = 0;
    updateCartUI();
    toggleCart();
}

// Smooth scrolling for nav links
document.querySelectorAll('a[href^="#"]').forEach(anchor => {
    anchor.addEventListener('click', function (e) {
        e.preventDefault();
        document.querySelector(this.getAttribute('href')).scrollIntoView({
            behavior: 'smooth'
        });
    });
});

// Contact form submission (demo)
document.querySelector('.contact-form').addEventListener('submit', function(e) {
    e.preventDefault();
    alert('Message sent! (Integrate with backend here)');
    this.reset();
});
