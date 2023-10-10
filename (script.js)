// Sample blog posts data (replace this with your actual blog post data)
const blogPosts = [
    { title: 'Post 1', content: 'This is the content of Post 1.' },
    { title: 'Post 2', content: 'This is the content of Post 2.' },
    // Add more blog posts as needed
];

// Function to display blog posts dynamically
function displayBlogPosts() {
    const blogPostsSection = document.getElementById('blog-posts');
    blogPosts.forEach(post => {
        const postElement = document.createElement('div');
        postElement.classList.add('blog-post');
        postElement.innerHTML = `<h3>${post.title}</h3><p>${post.content}</p>`;
        blogPostsSection.appendChild(postElement);
    });
}

// Call the function to display blog posts when the page loads
window.onload = displayBlogPosts;
