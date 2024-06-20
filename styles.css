// Show "Back to Top" button when user scrolls down
window.addEventListener('scroll', function() {
    const backToTopButton = document.getElementById('back-to-top');
    if (window.scrollY > 200) {
        backToTopButton.style.display = 'block';
    } else {
        backToTopButton.style.display = 'none';
    }
});

// Scroll to top when "Back to Top" button is clicked
document.getElementById('back-to-top').addEventListener('click', function() {
    window.scrollTo({ top: 0, behavior: 'smooth' });
});

// Toggle "Publications" submenu when "Publications" menu item is clicked
document.getElementById('publications-menu').addEventListener('click', function(event) {
    event.preventDefault();
    var submenu = document.getElementById('publications-submenu');
    if (submenu.style.display === 'block') {
        submenu.style.display = 'none';
    } else {
        submenu.style.display = 'block';
    }
});

// Hide "Publications" submenu when clicking outside
document.addEventListener('click', function(event) {
    var isClickInside = document.getElementById('publications-menu').contains(event.target) ||
                        document.getElementById('publications-submenu').contains(event.target);
    var submenu = document.getElementById('publications-submenu');
    if (!isClickInside && submenu.style.display === 'block') {
        submenu.style.display = 'none';
    }
});
