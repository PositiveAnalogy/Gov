
<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Meu Site Gov</title>
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/css/bootstrap.min.css" rel="stylesheet">
    <link href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0-beta3/css/all.min.css" rel="stylesheet">
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f8f9fa;
        }
        .navbar {
            background-color: #004a80;
        }
        .navbar-brand {
            color: #fff !important;
            font-weight: bold;
        }
        .nav-link {
            color: #fff !important;
        }
        .nav-link:hover {
            color: #f8f9fa !important;
            text-decoration: underline;
        }
        .footer {
            background-color: #004a80;
            color: #fff;
            padding: 20px 0;
            text-align: center;
        }
        .service-card {
            background-color: #fff;
            border: 1px solid #ddd;
            border-radius: 8px;
            padding: 20px;
            margin-bottom: 20px;
            transition: transform 0.2s;
        }
        .service-card:hover {
            transform: translateY(-5px);
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
        }
        .service-icon {
            font-size: 2rem;
            color: #004a80;
            margin-bottom: 10px;
        }
        .search-bar {
            max-width: 600px;
            margin: 0 auto;
        }
    </style>
</head>
<body>
    <!-- Cabeçalho -->
    <nav class="navbar navbar-expand-lg navbar-dark">
        <div class="container">
            <a class="navbar-brand" href="#">
                <i class="fas fa-landmark"></i> Meu Site Gov
            </a>
            <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav">
                <span class="navbar-toggler-icon"></span>
            </button>
            <div class="collapse navbar-collapse" id="navbarNav">
                <ul class="navbar-nav ms-auto">
                    <li class="nav-item dropdown">
                        <a class="nav-link dropdown-toggle" href="#" id="navbarDropdown" role="button" data-bs-toggle="dropdown">
                            <i class="fas fa-user"></i> Área do Cidadão
                        </a>
                        <ul class="dropdown-menu">
                            <li><a class="dropdown-item" href="#">Meus Dados</a></li>
                            <li><a class="dropdown-item" href="#">Meus Serviços</a></li>
                            <li><a class="dropdown-item" href="#">Sair</a></li>
                        </ul>
                    </li>
                    <li class="nav-item"><a class="nav-link" href="#"><i class="fas fa-bell"></i> Notificações</a></li>
                    <li class="nav-item"><a class="nav-link" href="#"><i class="fas fa-question-circle"></i> Ajuda</a></li>
                </ul>
            </div>
        </div>
    </nav>

    <!-- Conteúdo principal -->
    <div class="container my-5">
        <div class="text-center mb-5">
            <h1>Bem-vindo ao Meu Site Gov</h1>
            <p class="lead">Encontre os serviços públicos de forma rápida e fácil.</p>
            <form class="search-bar">
                <div class="input-group">
                    <input type="text" class="form-control" placeholder="Buscar serviços..." aria-label="Buscar">
                    <button class="btn btn-success" type="submit"><i class="fas fa-search"></i> Buscar</button>
                </div>
            </form>
        </div>

        <!-- Seção de Serviços -->
        <div class="row">
            <div class="col-md-4">
                <div class="service-card text-center">
                    <div class="service-icon">
                        <i class="fas fa-id-card"></i>
                    </div>
                    <h3>Documentos</h3>
                    <p>Emita ou renove seus documentos pessoais.</p>
                    <a href="#" class="btn btn-outline-primary">Acessar</a>
                </div>
            </div>
            <div class="col-md-4">
                <div class="service-card text-center">
                    <div class="service-icon">
                        <i class="fas fa-hand-holding-usd"></i>
                    </div>
                    <h3>Benefícios</h3>
                    <p>Consulte ou solicite benefícios sociais.</p>
                    <a href="#" class="btn btn-outline-primary">Acessar</a>
                </div>
            </div>
            <div class="col-md-4">
                <div class="service-card text-center">
                    <div class="service-icon">
                        <i class="fas fa-calendar-check"></i>
                    </div>
                    <h3>Agendamentos</h3>
                    <p>Agende serviços públicos online.</p>
                    <a href="#" class="btn btn-outline-primary">Acessar</a>
                </div>
            </div>
        </div>
    </div>

    <!-- Rodapé -->
    <footer class="footer">
        <div class="container">
            <p>&copy; 2025 Meu Site Gov. Todos os direitos reservados.</p>
            <p>
                <a href="#" class="text-light">Termos de Uso</a> | 
                <a href="#" class="text-light">Política de Privacidade</a>
            </p>
        </div>
    </footer>

    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/js/bootstrap.bundle.min.js"></script>
</body>
</html>
