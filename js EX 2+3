function toggleVisibility(elementId) {
    const element = document.getElementById(elementId);
    if (element.classList.contains('visible')) {
        element.classList.remove('visible');
        element.classList.add('hidden');
    } else {
        element.classList.remove('hidden');
        element.classList.add('visible');
    }
}

document.addEventListener('DOMContentLoaded', () => {
    const changeTextButton = document.getElementById('changeTextButton');

    changeTextButton.addEventListener('click', () => {
        changeTextButton.textContent = 'you clicked to hard!! :(';
        changeTextButton.disabled = true;
    });
});
