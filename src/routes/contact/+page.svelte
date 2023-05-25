<h1>Свяжитесь с нами</h1>
<section>
    <p>Заполните форму ниже, чтобы отправить нам сообщение:</p>
    <form action="submit-form.php" method="post">
        <label for="name">Имя:</label>
        <input type="text" id="name" name="name" required>
        <label for="email">Почта:</label>
        <input type="email" id="email" name="email" required>
        <label for="message">Сообщение:</label>
        <textarea id="message" name="message" required></textarea>
        <input type="button" value="Send">
    </form>
</section>
<section>
    <h2>Поддержка</h2>
    <p>Если у вас есть вопросы ко мне, то пишите на почту: <a href="mailto:support@example.com">kostinaav2006@gmail.com</a>.</p>
</section>

<style>
    body {
	font-family: Arial, sans-serif;
	margin: 0;
	padding: 0;
}

header {
	background-color: #333;
	color: #fff;
	padding: 20px;
}

header h1 {
	margin: 0;
}

main {
	max-width: 800px;
	margin: 0 auto;
	padding: 20px;
}

section {
	margin-bottom: 40px;
}

h2 {
	margin-top: 0;
}

form label {
	display: block;
	margin-bottom: 5px;
}

form input,
form textarea {
	display: block;
	width: 100%;
	padding: 10px;
	margin-bottom: 20px;
	border: 1px solid #ccc;
	border-radius: 5px;
}

form input[type="button"] {
	background-color: #333;
	color: #fff;
	border: none;
	border-radius: 5px;
	padding: 10px 20px;
	cursor: pointer;
}

form input[type="button"]:hover {
	background-color: #555;
}

a {
	color: #333;
	text-decoration: none;
}

footer {
	background-color: #333;
	color: #fff;
	padding: 20px;
	text-align: center;
}
</style>