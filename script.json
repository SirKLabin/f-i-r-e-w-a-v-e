// Cursor Glow Effect
const cursor = document.createElement('div');
cursor.classList.add('cursor');
document.body.appendChild(cursor);

document.addEventListener('mousemove', (e) => {
  cursor.style.transform = `translate(${e.clientX - 10}px, ${e.clientY - 10}px)`;
});

document.addEventListener('mouseenter', () => {
  cursor.style.opacity = 1;
});

document.addEventListener('mouseleave', () => {
  cursor.style.opacity = 0;
});