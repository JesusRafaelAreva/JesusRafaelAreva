<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Rafael - Estudiante de Ingeniería</title>
    <style>
        body {
            font-family: 'Arial', sans-serif;
            background-color: #f0f0f0;
            color: #333;
            display: flex;
            flex-direction: column;
            align-items: center;
            justify-content: center;
            height: 100vh;
            margin: 0;
            padding: 20px;
        }

        h1, h2, h3 {
            margin: 0;
            animation: fadeInUp 1s ease-in-out;
        }

        h1 {
            font-size: 3em;
            margin-bottom: 0.2em;
        }

        h2 {
            font-size: 2em;
            margin-bottom: 0.5em;
        }

        h3 {
            font-size: 1.5em;
            margin-bottom: 1em;
        }

        .skills {
            display: flex;
            flex-wrap: wrap;
            justify-content: center;
            gap: 10px;
            animation: fadeInUp 1.5s ease-in-out;
        }

        .skills a {
            text-decoration: none;
            animation: bounceIn 2s infinite;
        }

        @keyframes fadeInUp {
            from {
                opacity: 0;
                transform: translateY(20px);
            }
            to {
                opacity: 1;
                transform: translateY(0);
            }
        }

        @keyframes bounceIn {
            0%, 20%, 50%, 80%, 100% {
                transform: translateY(0);
            }
            40% {
                transform: translateY(-10px);
            }
            60% {
                transform: translateY(-5px);
            }
        }
    </style>
</head>
<body>
    <h1>👋 ¡Hola! Soy Rafael</h1>
    <h2>🎓 Estudiante de Ingeniería</h2>
    <h3>🚀 Habilidades Técnicas:</h3>
    <div class="skills">
        <a href="https://flutter.dev" target="_blank">
            <img src="https://img.shields.io/badge/Flutter-02569B?style=for-the-badge&logo=flutter&logoColor=white" alt="Flutter">
        </a>
        <a href="https://developer.mozilla.org/en-US/docs/Web/JavaScript" target="_blank">
            <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black" alt="JavaScript">
        </a>
        <a href="https://www.typescriptlang.org" target="_blank">
            <img src="https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white" alt="TypeScript">
        </a>
        <a href="https://nodejs.org" target="_blank">
            <img src="https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=node.js&logoColor=white" alt="Node.js">
        </a>
        <a href="https://www.php.net" target="_blank">
            <img src="https://img.shields.io/badge/PHP-777BB4?style=for-the-badge&logo=php&logoColor=white" alt="PHP">
        </a>
        <a href="https://laravel.com" target="_blank">
            <img src="https://img.shields.io/badge/Laravel-FF2D20?style=for-the-badge&logo=laravel&logoColor=white" alt="Laravel">
        </a>
        <a href="https://www.mysql.com" target="_blank">
            <img src="https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white" alt="MySQL">
        </a>
        <a href="https://firebase.google.com" target="_blank">
            <img src="https://img.shields.io/badge/Firebase-FFCA28?style=for-the-badge&logo=firebase&logoColor=black" alt="Firebase">
        </a>
        <a href="https://git-scm.com" target="_blank">
            <img src="https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white" alt="Git">
        </a>
        <a href="https://github.com" target="_blank">
            <img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub">
        </a>
        <a href="https://gitlab.com" target="_blank">
            <img src="https://img.shields.io/badge/GitLab-FC6D26?style=for-the-badge&logo=gitlab&logoColor=white" alt="GitLab">
        </a>
        <a href="https://www.postman.com" target="_blank">
            <img src="https://img.shields.io/badge/Postman-FF6C37?style=for-the-badge&logo=postman&logoColor=white" alt="Postman">
        </a>
    </div>
</body>
</html>
