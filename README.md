<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Lohan.Tec - Manutenção e Montagem de Computadores Profissional</title>
    <meta name="description" content="Lohan.Tec - Especialista em manutenção de computadores, notebooks e montagem de PCs personalizados. Atendimento a domicílio e garantia.">
    <meta name="keywords" content="manutenção computador, montagem pc, assistência técnica, notebook, formatação, hardware, software">
    <meta property="og:title" content="Lohan.Tec - Soluções em Tecnologia">
    <meta property="og:description" content="Serviços especializados em manutenção e montagem de computadores">
    <meta property="og:type" content="website">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/OwlCarousel2/2.3.4/assets/owl.carousel.min.css">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/OwlCarousel2/2.3.4/assets/owl.theme.default.min.css">
    <style>
        :root {
            --azul-escuro: #1e3a5f;
            --azul-medio: #2c5282;
            --azul-claro: #3182ce;
            --azul-suave: #bee3f8;
            --branco: #ffffff;
            --branco-gelo: #f7fafc;
            --cinza-claro: #edf2f7;
            --cinza-medio: #e2e8f0;
            --cinza-escuro: #4a5568;
            --verde: #38a169;
            --verde-claro: #c6f6d5;
            --laranja: #dd6b20;
            --laranja-claro: #fed7d7;
            --gradiente: linear-gradient(135deg, var(--azul-escuro) 0%, var(--azul-medio) 100%);
            --gradiente-claro: linear-gradient(135deg, var(--azul-suave) 0%, var(--branco) 100%);
        }
        
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
        }
        
        body {
            background-color: var(--branco-gelo);
            color: var(--cinza-escuro);
            line-height: 1.6;
            overflow-x: hidden;
        }
        
        /* Header e Navegação */
        header {
            background: var(--gradiente);
            color: var(--branco);
            padding: 1rem 0;
            box-shadow: 0 4px 12px rgba(30, 58, 95, 0.2);
            position: fixed;
            width: 100%;
            top: 0;
            z-index: 1000;
        }
        
        .header-container {
            max-width: 1200px;
            margin: 0 auto;
            padding: 0 1rem;
            display: flex;
            justify-content: space-between;
            align-items: center;
        }
        
        .logo {
            font-size: 1.8rem;
            font-weight: bold;
            display: flex;
            align-items: center;
            gap: 10px;
        }
        
        .logo i {
            color: var(--branco);
            background: var(--azul-claro);
            border-radius: 50%;
            padding: 8px;
        }
        
        .nav-menu {
            display: flex;
            list-style: none;
            gap: 2rem;
        }
        
        .nav-menu a {
            color: var(--branco);
            text-decoration: none;
            font-weight: 500;
            transition: color 0.3s ease;
        }
        
        .nav-menu a:hover {
            color: var(--azul-suave);
        }
        
        .mobile-menu-btn {
            display: none;
            background: none;
            border: none;
            color: var(--branco);
            font-size: 1.5rem;
            cursor: pointer;
        }
        
        /* Hero Section */
        .hero {
            margin-top: 80px;
            display: flex;
            flex-wrap: wrap;
            align-items: center;
            padding: 4rem 1rem;
            background: var(--gradiente);
            color: var(--branco);
            position: relative;
            overflow: hidden;
            min-height: 80vh;
        }
        
        .hero::before {
            content: "";
            position: absolute;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            background: url('data:image/svg+xml;utf8,<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 100 100" preserveAspectRatio="none"><path d="M0,0 L100,0 L100,100 Z" fill="rgba(255,255,255,0.1)"/></svg>');
            background-size: cover;
            transform: scaleX(-1);
        }
        
        .hero-content {
            max-width: 1200px;
            margin: 0 auto;
            display: flex;
            flex-wrap: wrap;
            align-items: center;
            width: 100%;
        }
        
        .hero-text {
            flex: 1;
            min-width: 300px;
            padding: 2rem;
            position: relative;
            z-index: 1;
        }
        
        .hero-image {
            flex: 1;
            min-width: 300px;
            text-align: center;
            position: relative;
            z-index: 1;
            animation: float 6s ease-in-out infinite;
        }
        
        @keyframes float {
            0% { transform: translateY(0px); }
            50% { transform: translateY(-15px); }
            100% { transform: translateY(0px); }
        }
        
        .hero-image img {
            max-width: 100%;
            border-radius: 15px;
            box-shadow: 0 10px 30px rgba(0,0,0,0.3);
            display: block;
            height: auto;
            border: 5px solid rgba(255,255,255,0.2);
        }
        
        h1 {
            font-size: 3rem;
            margin-bottom: 1.5rem;
            color: var(--branco);
        }
        
        h2 {
            font-size: 2.2rem;
            margin-bottom: 1.5rem;
            color: var(--azul-escuro);
            position: relative;
            display: inline-block;
        }
        
        h2::after {
            content: "";
            position: absolute;
            bottom: -10px;
            left: 0;
            width: 80px;
            height: 4px;
            background: var(--azul-claro);
            border-radius: 2px;
        }
        
        .section-title {
            text-align: center;
            margin-bottom: 3rem;
        }
        
        .section-title h2::after {
            left: 50%;
            transform: translateX(-50%);
        }
        
        p {
            margin-bottom: 1.5rem;
            font-size: 1.1rem;
        }
        
        /* Botões */
        .btn {
            display: inline-block;
            background-color: var(--azul-claro);
            color: var(--branco);
            padding: 1rem 2rem;
            border: none;
            border-radius: 8px;
            text-decoration: none;
            font-weight: bold;
            cursor: pointer;
            transition: all 0.3s ease;
            margin: 0.5rem;
            box-shadow: 0 4px 12px rgba(49, 130, 206, 0.3);
            position: relative;
            overflow: hidden;
        }
        
        .btn::before {
            content: "";
            position: absolute;
            top: 0;
            left: -100%;
            width: 100%;
            height: 100%;
            background: linear-gradient(90deg, transparent, rgba(255,255,255,0.3), transparent);
            transition: 0.5s;
        }
        
        .btn:hover::before {
            left: 100%;
        }
        
        .btn:hover {
            transform: translateY(-3px);
            box-shadow: 0 8px 20px rgba(49, 130, 206, 0.5);
            background-color: var(--azul-medio);
        }
        
        .btn-whatsapp {
            background-color: var(--verde);
            box-shadow: 0 4px 12px rgba(56, 161, 105, 0.3);
        }
        
        .btn-whatsapp:hover {
            box-shadow: 0 8px 20px rgba(56, 161, 105, 0.5);
            background-color: #2f855a;
        }
        
        .btn-instagram {
            background-color: var(--azul-medio);
            box-shadow: 0 4px 12px rgba(44, 82, 130, 0.3);
        }
        
        .btn-instagram:hover {
            box-shadow: 0 8px 20px rgba(44, 82, 130, 0.5);
            background-color: var(--azul-escuro);
        }
        
        .btn-orcamento {
            background-color: var(--laranja);
            box-shadow: 0 4px 12px rgba(221, 107, 32, 0.3);
            margin-top: 30px;
        }
        
        .btn-orcamento:hover {
            box-shadow: 0 8px 20px rgba(221, 107, 32, 0.5);
            background-color: #c05621;
        }
        
        /* Serviços */
        .services {
            padding: 5rem 1rem;
            text-align: center;
            background-color: var(--branco);
        }
        
        .service-cards {
            display: flex;
            flex-wrap: wrap;
            justify-content: center;
            gap: 2rem;
            margin-top: 3rem;
        }
        
        .card {
            background-color: var(--branco);
            border-radius: 12px;
            box-shadow: 0 8px 20px rgba(30, 58, 95, 0.1);
            padding: 2rem;
            width: 300px;
            transition: all 0.3s ease;
            border-top: 4px solid var(--azul-claro);
            position: relative;
            overflow: hidden;
        }
        
        .card::before {
            content: "";
            position: absolute;
            top: 0;
            left: 0;
            width: 100%;
            height: 4px;
            background: var(--gradiente);
        }
        
        .card:hover {
            transform: translateY(-10px);
            box-shadow: 0 15px 30px rgba(30, 58, 95, 0.15);
        }
        
        .card-icon {
            font-size: 3rem;
            color: var(--azul-claro);
            margin-bottom: 1.5rem;
        }
        
        .card h3 {
            font-size: 1.5rem;
            margin-bottom: 1rem;
            color: var(--azul-escuro);
        }
        
        .card p {
            color: var(--cinza-escuro);
            font-size: 1rem;
        }
        
        /* Montagem PC */
        .montagem-pc {
            padding: 5rem 1rem;
            background: var(--gradiente-claro);
            text-align: center;
        }
        
        .montagem-content {
            max-width: 800px;
            margin: 0 auto;
        }
        
        .montagem-content h2 {
            color: var(--azul-escuro);
        }
        
        .montagem-content h2::after {
            background: var(--laranja);
            bottom: -10px;
            left: 50%;
            transform: translateX(-50%);
            width: 100px;
            height: 4px;
        }
        
        .features {
            display: flex;
            flex-wrap: wrap;
            justify-content: center;
            gap: 2rem;
            margin-top: 3rem;
        }
        
        .feature {
            flex: 1;
            min-width: 250px;
            background: var(--branco);
            padding: 2rem;
            border-radius: 10px;
            box-shadow: 0 5px 15px rgba(30, 58, 95, 0.1);
            border-left: 4px solid var(--azul-claro);
        }
        
        .feature i {
            font-size: 2.5rem;
            margin-bottom: 1rem;
            color: var(--azul-claro);
        }
        
        /* Calculadora de Orçamento */
        .calculadora-orcamento {
            background: var(--branco);
            padding: 3rem 2rem;
            border-radius: 15px;
            box-shadow: 0 10px 30px rgba(0,0,0,0.1);
            max-width: 600px;
            margin: 3rem auto;
        }
        
        .calculadora-orcamento h3 {
            color: var(--azul-escuro);
            margin-bottom: 1.5rem;
            text-align: center;
        }
        
        .calculadora-group {
            margin-bottom: 1.5rem;
        }
        
        .calculadora-group label {
            display: block;
            margin-bottom: 0.5rem;
            font-weight: bold;
            color: var(--azul-escuro);
        }
        
        .calculadora-group select, .calculadora-group input {
            width: 100%;
            padding: 0.8rem;
            border: 2px solid var(--cinza-medio);
            border-radius: 8px;
            font-size: 1rem;
        }
        
        .resultado-orcamento {
            background: var(--verde-claro);
            padding: 1.5rem;
            border-radius: 8px;
            margin-top: 1.5rem;
            text-align: center;
            border: 2px solid var(--verde);
        }
        
        .valor-orcamento {
            font-size: 2rem;
            font-weight: bold;
            color: var(--verde);
            margin: 1rem 0;
        }
        
        /* Depoimentos */
        .depoimentos {
            padding: 5rem 1rem;
            background: var(--gradiente);
            color: var(--branco);
        }
        
        .depoimentos h2 {
            color: var(--branco);
        }
        
        .depoimentos h2::after {
            background: var(--laranja);
        }
        
        .owl-carousel {
            margin-top: 3rem;
        }
        
        .depoimento-card {
            background: rgba(255,255,255,0.1);
            padding: 2rem;
            border-radius: 10px;
            margin: 1rem;
            backdrop-filter: blur(10px);
        }
        
        .depoimento-texto {
            font-style: italic;
            margin-bottom: 1rem;
            line-height: 1.6;
        }
        
        .depoimento-cliente {
            display: flex;
            align-items: center;
            gap: 1rem;
        }
        
        .cliente-avatar {
            width: 50px;
            height: 50px;
            border-radius: 50%;
            background: var(--laranja);
            display: flex;
            align-items: center;
            justify-content: center;
            color: white;
            font-weight: bold;
        }
        
        .cliente-info h4 {
            margin-bottom: 0.2rem;
        }
        
        .cliente-info p {
            margin: 0;
            opacity: 0.8;
            font-size: 0.9rem;
        }
        
        /* Galeria */
        .galeria {
            padding: 5rem 1rem;
            background: var(--branco);
        }
        
        .galeria-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 1.5rem;
            margin-top: 3rem;
        }
        
        .galeria-item {
            position: relative;
            border-radius: 10px;
            overflow: hidden;
            box-shadow: 0 5px 15px rgba(0,0,0,0.1);
            transition: transform 0.3s ease;
        }
        
        .galeria-item:hover {
            transform: translateY(-5px);
        }
        
        .galeria-item img {
            width: 100%;
            height: 250px;
            object-fit: cover;
            display: block;
        }
        
        .galeria-legenda {
            position: absolute;
            bottom: 0;
            left: 0;
            right: 0;
            background: rgba(30, 58, 95, 0.9);
            color: white;
            padding: 1rem;
            text-align: center;
        }
        
        /* Formulário de Agendamento */
        .booking {
            background-color: var(--branco);
            padding: 5rem 1rem;
            margin: 2rem 0;
            border-radius: 15px;
            box-shadow: 0 10px 25px rgba(30, 58, 95, 0.1);
            max-width: 1000px;
            margin-left: auto;
            margin-right: auto;
        }
        
        form {
            max-width: 600px;
            margin: 0 auto;
        }
        
        .form-group {
            margin-bottom: 1.5rem;
        }
        
        label {
            display: block;
            margin-bottom: 0.5rem;
            font-weight: bold;
            color: var(--azul-escuro);
        }
        
        input, select, textarea {
            width: 100%;
            padding: 1rem;
            border: 2px solid var(--cinza-medio);
            border-radius: 8px;
            font-size: 1rem;
            transition: all 0.3s ease;
            background-color: var(--branco-gelo);
        }
        
        input:focus, select:focus, textarea:focus {
            border-color: var(--azul-claro);
            box-shadow: 0 0 0 3px rgba(49, 130, 206, 0.2);
            outline: none;
            background-color: var(--branco);
        }
        
        .service-option {
            display: flex;
            align-items: center;
            margin-bottom: 0.5rem;
        }
        
        .service-option input {
            width: auto;
            margin-right: 0.5rem;
        }
        
        .address-field {
            display: none;
            margin-top: 1rem;
            animation: fadeIn 0.5s ease;
        }
        
        .file-upload {
            border: 2px dashed var(--cinza-medio);
            padding: 2rem;
            text-align: center;
            border-radius: 8px;
            cursor: pointer;
            transition: all 0.3s ease;
        }
        
        .file-upload:hover {
            border-color: var(--azul-claro);
            background: var(--azul-suave);
        }
        
        .file-upload i {
            font-size: 2rem;
            color: var(--azul-claro);
            margin-bottom: 1rem;
        }
        
        @keyframes fadeIn {
            from { opacity: 0; transform: translateY(-10px); }
            to { opacity: 1; transform: translateY(0); }
        }
        
        /* Footer */
        footer {
            background: var(--gradiente);
            color: var(--branco);
            text-align: center;
            padding: 3rem 1rem;
            margin-top: 4rem;
        }
        
        .footer-content {
            display: flex;
            flex-wrap: wrap;
            justify-content: space-between;
            align-items: center;
            max-width: 1000px;
            margin: 0 auto;
        }
        
        .footer-logo {
            font-size: 2rem;
            font-weight: bold;
            margin-bottom: 1rem;
        }
        
        .social-links {
            margin: 1rem 0;
        }
        
        .social-links a {
            display: inline-flex;
            align-items: center;
            justify-content: center;
            width: 50px;
            height: 50px;
            background: rgba(255,255,255,0.1);
            color: var(--branco);
            margin: 0 0.5rem;
            font-size: 1.5rem;
            text-decoration: none;
            border-radius: 50%;
            transition: all 0.3s ease;
        }
        
        .social-links a:hover {
            background: var(--azul-claro);
            transform: translateY(-5px);
        }
        
        .copyright {
            margin-top: 2rem;
            font-size: 0.9rem;
            opacity: 0.8;
            width: 100%;
        }
        
        /* Admin Panel */
        .admin-panel {
            display: none;
            position: fixed;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            background-color: rgba(30, 58, 95, 0.95);
            z-index: 2000;
            justify-content: center;
            align-items: center;
            padding: 1rem;
        }
        
        .admin-content {
            background-color: var(--branco);
            padding: 2rem;
            border-radius: 15px;
            width: 95%;
            max-width: 1200px;
            max-height: 90vh;
            overflow-y: auto;
            box-shadow: 0 10px 30px rgba(0,0,0,0.3);
        }
        
        .admin-header {
            display: flex;
            justify-content: space-between;
            align-items: center;
            margin-bottom: 2rem;
            padding-bottom: 1rem;
            border-bottom: 2px solid var(--cinza-medio);
        }
        
        .admin-tabs {
            display: flex;
            margin-bottom: 1.5rem;
            border-bottom: 1px solid var(--cinza-medio);
        }
        
        .admin-tab {
            padding: 0.8rem 1.5rem;
            background: none;
            border: none;
            cursor: pointer;
            font-size: 1rem;
            font-weight: bold;
            color: var(--azul-escuro);
            border-bottom: 3px solid transparent;
            transition: all 0.3s ease;
        }
        
        .admin-tab.active {
            color: var(--azul-claro);
            border-bottom: 3px solid var(--azul-claro);
        }
        
        .admin-tab:hover {
            color: var(--azul-claro);
        }
        
        .tab-content {
            display: none;
        }
        
        .tab-content.active {
            display: block;
            animation: fadeIn 0.5s ease;
        }
        
        .admin-table {
            width: 100%;
            border-collapse: collapse;
            margin-top: 1rem;
            box-shadow: 0 5px 15px rgba(0,0,0,0.05);
            border-radius: 10px;
            overflow: hidden;
        }
        
        .admin-table th, .admin-table td {
            padding: 1rem;
            text-align: left;
            border-bottom: 1px solid var(--cinza-medio);
        }
        
        .admin-table th {
            background-color: var(--azul-escuro);
            color: white;
            font-weight: 600;
        }
        
        .admin-table tr:nth-child(even) {
            background-color: var(--branco-gelo);
        }
        
        .admin-table tr:hover {
            background-color: var(--cinza-claro);
        }
        
        .status-btn {
            padding: 0.5rem 1rem;
            border: none;
            border-radius: 5px;
            cursor: pointer;
            margin-right: 0.3rem;
            font-weight: bold;
            transition: all 0.3s ease;
        }
        
        .status-pendente {
            background-color: var(--laranja-claro);
            color: var(--laranja);
            border: 1px solid var(--laranja);
        }
        
        .status-concluido {
            background-color: var(--verde-claro);
            color: var(--verde);
            border: 1px solid var(--verde);
        }
        
        .delete-btn {
            background-color: var(--azul-escuro);
            color: white;
            padding: 0.5rem 1rem;
            border: none;
            border-radius: 5px;
            cursor: pointer;
            transition: all 0.3s ease;
        }
        
        .delete-btn:hover {
            background-color: var(--azul-medio);
        }
        
        .stats-cards {
            display: flex;
            flex-wrap: wrap;
            gap: 1.5rem;
            margin-bottom: 2rem;
        }
        
        .stat-card {
            flex: 1;
            min-width: 200px;
            background: var(--gradiente);
            color: white;
            padding: 1.5rem;
            border-radius: 10px;
            text-align: center;
            box-shadow: 0 5px 15px rgba(0,0,0,0.1);
        }
        
        .stat-number {
            font-size: 2.5rem;
            font-weight: bold;
            margin-bottom: 0.5rem;
        }
        
        .stat-label {
            font-size: 1rem;
            opacity: 0.9;
        }
        
        .chart-container {
            background: var(--branco);
            padding: 2rem;
            border-radius: 10px;
            box-shadow: 0 5px 15px rgba(0,0,0,0.1);
            margin-top: 2rem;
        }
        
        .backup-section {
            background: var(--branco-gelo);
            padding: 2rem;
            border-radius: 10px;
            margin-top: 2rem;
            border: 2px solid var(--cinza-medio);
        }
        
        /* Notificações */
        .notification {
            position: fixed;
            top: 100px;
            right: 20px;
            background: var(--verde);
            color: white;
            padding: 1rem 2rem;
            border-radius: 8px;
            box-shadow: 0 5px 15px rgba(0,0,0,0.2);
            z-index: 1500;
            transform: translateX(400px);
            transition: transform 0.3s ease;
        }
        
        .notification.show {
            transform: translateX(0);
        }
        
        .notification.error {
            background: var(--laranja);
        }
        
        /* Responsividade */
        @media (max-width: 768px) {
            .header-container {
                flex-direction: column;
                gap: 1rem;
            }
            
            .nav-menu {
                flex-direction: column;
                text-align: center;
                gap: 1rem;
                display: none;
            }
            
            .nav-menu.active {
                display: flex;
            }
            
            .mobile-menu-btn {
                display: block;
            }
            
            .hero {
                margin-top: 140px;
                flex-direction: column;
                text-align: center;
                padding: 3rem 1rem;
            }
            
            h1 {
                font-size: 2.2rem;
            }
            
            h2 {
                font-size: 1.8rem;
            }
            
            .service-cards {
                flex-direction: column;
                align-items: center;
            }
            
            .card {
                width: 100%;
                max-width: 350px;
            }
            
            .admin-table {
                font-size: 0.8rem;
            }
            
            .admin-table th, .admin-table td {
                padding: 0.7rem;
            }
            
            .hero-image {
                margin-top: 1.5rem;
            }
            
            .btn {
                display: block;
                width: 100%;
                margin: 0.5rem 0;
                text-align: center;
            }
            
            .footer-content {
                flex-direction: column;
                text-align: center;
            }
            
            .admin-tabs {
                flex-wrap: wrap;
            }
            
            .admin-tab {
                flex: 1;
                min-width: 120px;
                text-align: center;
            }
            
            .features {
                flex-direction: column;
            }
        }
        
        @media (max-width: 480px) {
            .logo {
                font-size: 1.5rem;
            }
            
            h1 {
                font-size: 1.8rem;
            }
            
            h2 {
                font-size: 1.5rem;
            }
            
            .card {
                padding: 1.5rem;
            }
            
            .hero-image img {
                max-height: 200px;
            }
            
            .stats-cards {
                flex-direction: column;
            }
        }
    </style>
</head>
<body>
    <!-- Header -->
    <header>
        <div class="header-container">
            <div class="logo">
                <i class="fas fa-laptop-code"></i>
                Lohan.Tec
            </div>
            <nav>
                <ul class="nav-menu">
                    <li><a href="#servicos">Serviços</a></li>
                    <li><a href="#montagem">Montagem</a></li>
                    <li><a href="#depoimentos">Depoimentos</a></li>
                    <li><a href="#galeria">Galeria</a></li>
                    <li><a href="#agendar">Agendar</a></li>
                </ul>
                <button class="mobile-menu-btn">
                    <i class="fas fa-bars"></i>
                </button>
            </nav>
            <button id="admin-btn" class="btn">
                <i class="fas fa-cog"></i> Admin
            </button>
        </div>
    </header>

    <!-- Hero Section -->
    <section class="hero">
        <div class="hero-content">
            <div class="hero-text">
                <h1>Tecnologia com Excelência</h1>
                <p>Oferecemos serviços especializados em manutenção de computadores, notebooks e montagem de PCs personalizados de acordo com seu orçamento e necessidades.</p>
                <a href="#agendar" class="btn">
                    <i class="fas fa-calendar-check"></i> Agendar Serviço
                </a>
                <a href="#montagem" class="btn btn-orcamento">
                    <i class="fas fa-desktop"></i> Montagem de PC
                </a>
                <a href="https://wa.me/5585997593798" class="btn btn-whatsapp" target="_blank">
                    <i class="fab fa-whatsapp"></i> Fale no WhatsApp
                </a>
            </div>
            <div class="hero-image">
                <img src="https://images.unsplash.com/photo-1563013544-824ae1b704d3?ixlib=rb-1.2.1&auto=format&fit=crop&w=500&q=60" alt="Setup de computador moderno e organizado">
            </div>
        </div>
    </section>

    <!-- Serviços -->
    <section id="servicos" class="services">
        <div class="container">
            <div class="section-title">
                <h2>Nossos Serviços</h2>
                <p>Soluções completas para suas necessidades tecnológicas</p>
            </div>
            
            <div class="service-cards">
                <div class="card">
                    <div class="card-icon">
                        <i class="fas fa-tools"></i>
                    </div>
                    <h3>Manutenção de Hardware</h3>
                    <p>Troca de peças, limpeza interna, upgrades e reparos em geral para computadores e notebooks.</p>
                </div>
                
                <div class="card">
                    <div class="card-icon">
                        <i class="fas fa-code"></i>
                    </div>
                    <h3>Manutenção de Software</h3>
                    <p>Formatação, instalação de programas, remoção de vírus, otimização e configurações.</p>
                </div>
                
                <div class="card">
                    <div class="card-icon">
                        <i class="fas fa-home"></i>
                    </div>
                    <h3>Atendimento a Domicílio</h3>
                    <p>Comodidade e praticidade com nosso serviço de atendimento em sua casa ou empresa.</p>
                </div>
                
                <div class="card">
                    <div class="card-icon">
                        <i class="fas fa-desktop"></i>
                    </div>
                    <h3>Montagem de PCs</h3>
                    <p>Montamos computadores personalizados de acordo com seu orçamento e necessidades específicas.</p>
                </div>
            </div>
        </div>
    </section>

    <!-- Montagem PC -->
    <section id="montagem" class="montagem-pc">
        <div class="container">
            <div class="montagem-content">
                <h2>Montagem de PC Personalizado</h2>
                <p>Montamos o computador dos seus sonhos dentro do seu orçamento! Desde máquinas para escritório até setups gamers de alta performance.</p>
                
                <div class="features">
                    <div class="feature">
                        <i class="fas fa-cogs"></i>
                        <h3>Configuração Personalizada</h3>
                        <p>Selecionamos os melhores componentes de acordo com suas necessidades e orçamento.</p>
                    </div>
                    
                    <div class="feature">
                        <i class="fas fa-bolt"></i>
                        <h3>Alta Performance</h3>
                        <p>Garantimos o melhor custo-benefício para que sua máquina tenha o máximo desempenho.</p>
                    </div>
                    
                    <div class="feature">
                        <i class="fas fa-shield-alt"></i>
                        <h3>Garantia e Suporte</h3>
                        <p>Todos os nossos PCs montados contam com garantia e suporte técnico especializado.</p>
                    </div>
                </div>

                <!-- Calculadora de Orçamento -->
                <div class="calculadora-orcamento">
                    <h3>Simule seu Orçamento</h3>
                    <div class="calculadora-group">
                        <label for="tipo-pc">Tipo de PC:</label>
                        <select id="tipo-pc">
                            <option value="escritorio">Escritório/Básico</option>
                            <option value="multimidia">Multimídia</option>
                            <option value="gamer">Gamer</option>
                            <option value="estudos">Estudos/Trabalho</option>
                        </select>
                    </div>
                    <div class="calculadora-group">
                        <label for="orcamento">Orçamento Disponível (R$):</label>
                        <input type="number" id="orcamento" min="1000" max="10000" value="2500">
                    </div>
                    <div class="calculadora-group">
                        <label for="uso-pc">Uso Principal:</label>
                        <select id="uso-pc">
                            <option value="trabalho">Trabalho/Escritório</option>
                            <option value="estudos">Estudos</option>
                            <option value="games">Jogos</option>
                            <option value="design">Design/Edição</option>
                        </select>
                    </div>
                    <button class="btn" onclick="calcularOrcamento()">
                        <i class="fas fa-calculator"></i> Calcular Orçamento
                    </button>
                    <div class="resultado-orcamento" id="resultado-orcamento" style="display: none;">
                        <h4>Orçamento Estimado:</h4>
                        <div class="valor-orcamento" id="valor-orcamento">R$ 0,00</div>
                        <p id="descricao-orcamento"></p>
                        <a href="https://wa.me/5585997593798" class="btn btn-whatsapp" target="_blank">
                            Solicitar Orçamento Detalhado
                        </a>
                    </div>
                </div>
                
                <a href="https://wa.me/5585997593798?text=Olá! Gostaria de solicitar um orçamento para montagem de PC." class="btn btn-orcamento" target="_blank">
                    <i class="fas fa-calculator"></i> Solicitar Orçamento Personalizado
                </a>
            </div>
        </div>
    </section>

    <!-- Depoimentos -->
    <section id="depoimentos" class="depoimentos">
        <div class="container">
            <div class="section-title">
                <h2>O que nossos clientes dizem</h2>
                <p>Confira a experiência de quem já utilizou nossos serviços</p>
            </div>
            
            <div class="owl-carousel owl-theme">
                <div class="depoimento-card">
                    <div class="depoimento-texto">
                        "Meu notebook tava super lento e quase desisti dele. O Lohan deu um jeito rapidão e ainda explicou tudinho o que foi feito. Agora tá novinho!"
                    </div>
                    <div class="depoimento-cliente">
                        <div class="cliente-avatar">M</div>
                        <div class="cliente-info">
                            <h4>Maria Silva</h4>
                            <p>Manutenção de Notebook</p>
                        </div>
                    </div>
                </div>
                
                <div class="depoimento-card">
                    <div class="depoimento-texto">
                        "Queria montar um PC pra jogar mas tava perdido com as peças. O cara me ajudou a escolher tudo dentro do meu orçamento. Ficou show demais!"
                    </div>
                    <div class="depoimento-cliente">
                        <div class="cliente-avatar">J</div>
                        <div class="cliente-info">
                            <h4>João Santos</h4>
                            <p>PC Gamer Montado</p>
                        </div>
                    </div>
                </div>
                
                <div class="depoimento-card">
                    <div class="depoimento-texto">
                        "Não tinha como levar o PC na oficina, então pedi o atendimento em casa. Chegou no horário, foi super educado e resolveu na hora. Muito prático!"
                    </div>
                    <div class="depoimento-cliente">
                        <div class="cliente-avatar">A</div>
                        <div class="cliente-info">
                            <h4>Ana Costa</h4>
                            <p>Atendimento em Domicílio</p>
                        </div>
                    </div>
                </div>

                <div class="depoimento-card">
                    <div class="depoimento-texto">
                        "Meu computador deu problema bem na época de provas da facul. Salvaram minha vida, consertaram super rápido e ainda fizeram um preço especial pra estudante."
                    </div>
                    <div class="depoimento-cliente">
                        <div class="cliente-avatar">P</div>
                        <div class="cliente-info">
                            <h4>Pedro Almeida</h4>
                            <p>Formatação e Otimização</p>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Galeria -->
    <section id="galeria" class="galeria">
        <div class="container">
            <div class="section-title">
                <h2>Nossos Serviços em Imagens</h2>
                <p>Conheça um pouco do nosso trabalho</p>
            </div>
            
            <div class="galeria-grid">
                <div class="galeria-item">
                    <img src="https://images.unsplash.com/photo-1591799264318-7e6ef8ddb7ea?ixlib=rb-1.2.1&auto=format&fit=crop&w=500&q=60" alt="Montagem de computador">
                    <div class="galeria-legenda">
                        <h4>Montagem Personalizada</h4>
                    </div>
                </div>
                
                <div class="galeria-item">
                    <img src="https://images.unsplash.com/photo-1562408590-e32931084e23?ixlib=rb-1.2.1&auto=format&fit=crop&w=500&q=60" alt="Manutenção de equipamentos">
                    <div class="galeria-legenda">
                        <h4>Manutenção Especializada</h4>
                    </div>
                </div>
                
                <div class="galeria-item">
                    <img src="https://images.unsplash.com/photo-1581093458791-8a6b6d47d0b9?ixlib=rb-1.2.1&auto=format&fit=crop&w=500&q=60" alt="Configuração de software">
                    <div class="galeria-legenda">
                        <h4>Configuração de Software</h4>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Agendamento -->
    <section id="agendar" class="booking">
        <div class="container">
            <div class="section-title">
                <h2>Agende seu Atendimento</h2>
                <p>Preencha o formulário abaixo para agendar seu serviço</p>
            </div>
            
            <form id="booking-form">
                <div class="form-group">
                    <label for="nome">Nome completo</label>
                    <input type="text" id="nome" name="nome" required>
                </div>
                
                <div class="form-group">
                    <label for="telefone">Telefone para contato</label>
                    <input type="tel" id="telefone" name="telefone" required>
                </div>
                
                <div class="form-group">
                    <label for="email">E-mail (opcional)</label>
                    <input type="email" id="email" name="email">
                </div>
                
                <div class="form-group">
                    <label for="data-preferred">Data Preferencial</label>
                    <input type="date" id="data-preferred" name="data-preferred" min="<?php echo date('Y-m-d'); ?>">
                </div>
                
                <div class="form-group">
                    <label for="horario-preferred">Horário Preferencial</label>
                    <select id="horario-preferred" name="horario-preferred">
                        <option value="">Qualquer horário</option>
                        <option value="manha">Manhã (8h-12h)</option>
                        <option value="tarde">Tarde (13h-18h)</option>
                        <option value="noite">Noite (18h-21h)</option>
                    </select>
                </div>
                
                <div class="form-group">
                    <label>Tipo de atendimento</label>
                    <div class="service-option">
                        <input type="radio" id="domicilio" name="tipo-atendimento" value="domicilio">
                        <label for="domicilio">Atendimento a domicílio</label>
                    </div>
                    <div class="service-option">
                        <input type="radio" id="oficina" name="tipo-atendimento" value="oficina" checked>
                        <label for="oficina">Trazer o aparelho para a oficina</label>
                    </div>
                    
                    <div id="endereco-field" class="address-field">
                        <label for="endereco">Endereço para atendimento</label>
                        <input type="text" id="endereco" name="endereco" placeholder="Digite seu endereço completo">
                    </div>
                </div>
                
                <div class="form-group">
                    <label for="servico">Tipo de serviço</label>
                    <select id="servico" name="servico" required>
                        <option value="">Selecione...</option>
                        <option value="manutencao-hardware">Manutenção de Hardware</option>
                        <option value="manutencao-software">Manutenção de Software</option>
                        <option value="montagem-pc">Montagem de PC</option>
                        <option value="outro">Outro</option>
                    </select>
                </div>
                
                <div class="form-group">
                    <label for="aparelho">Tipo de aparelho</label>
                    <select id="aparelho" name="aparelho" required>
                        <option value="">Selecione...</option>
                        <option value="notebook">Notebook</option>
                        <option value="desktop">Computador Desktop</option>
                        <option value="all-in-one">All-in-One</option>
                        <option value="montagem">Montagem de PC</option>
                        <option value="outro">Outro</option>
                    </select>
                </div>
                
                <div class="form-group">
                    <label for="problema">Descreva o problema ou necessidade</label>
                    <textarea id="problema" name="problema" rows="4" placeholder="Descreva detalhadamente o problema do seu equipamento ou o que você precisa em caso de montagem de PC" required></textarea>
                </div>
                
                <div class="form-group">
                    <label>Anexar foto do problema (opcional)</label>
                    <div class="file-upload" onclick="document.getElementById('foto-problema').click()">
                        <i class="fas fa-cloud-upload-alt"></i>
                        <p>Clique para adicionar foto</p>
                        <input type="file" id="foto-problema" name="foto-problema" accept="image/*" style="display: none;">
                    </div>
                </div>
                
                <button type="submit" class="btn">
                    <i class="fas fa-paper-plane"></i> Enviar Agendamento
                </button>
            </form>
        </div>
    </section>

    <!-- Footer -->
    <footer>
        <div class="container">
            <div class="footer-content">
                <div class="footer-logo">Lohan.Tec</div>
                <p>Soluções completas em tecnologia</p>
                
                <div class="social-links">
                    <a href="https://www.instagram.com/lohan_tec?igsh=dml4YWFhN3kxY2li&utm_source=qr" target="_blank" title="Instagram">
                        <i class="fab fa-instagram"></i>
                    </a>
                    <a href="https://wa.me/5585997593798" target="_blank" title="WhatsApp">
                        <i class="fab fa-whatsapp"></i>
                    </a>
                    <a href="mailto:contato@lohantec.com" title="E-mail">
                        <i class="fas fa-envelope"></i>
                    </a>
                </div>
                
                <div class="copyright">
                    &copy; 2023 Lohan.Tec - Todos os direitos reservados
                </div>
            </div>
        </div>
    </footer>

    <!-- Painel Administrativo -->
    <div id="admin-panel" class="admin-panel">
        <div class="admin-content">
            <div class="admin-header">
                <h2>Painel Administrativo - Lohan.Tec</h2>
                <button id="close-admin" class="btn">
                    <i class="fas fa-times"></i> Fechar
                </button>
            </div>
            
            <div id="login-form">
                <h3>Acesso Restrito</h3>
                <p>Digite a senha para acessar o painel administrativo:</p>
                <input type="password" id="password" placeholder="Senha">
                <button onclick="checkPassword()" class="btn">Acessar</button>
            </div>
            
            <div id="admin-dashboard" style="display: none;">
                <div class="admin-tabs">
                    <button class="admin-tab active" onclick="openTab('agendamentos-tab')">
                        <i class="fas fa-calendar-alt"></i> Agendamentos
                    </button>
                    <button class="admin-tab" onclick="openTab('logs-tab')">
                        <i class="fas fa-history"></i> Logs de Acesso
                    </button>
                    <button class="admin-tab" onclick="openTab('estatisticas-tab')">
                        <i class="fas fa-chart-bar"></i> Estatísticas
                    </button>
                    <button class="admin-tab" onclick="openTab('backup-tab')">
                        <i class="fas fa-download"></i> Backup
                    </button>
                </div>
                
                <div id="agendamentos-tab" class="tab-content active">
                    <h3>Agendamentos Recebidos</h3>
                    <div class="stats-cards">
                        <div class="stat-card">
                            <div class="stat-number" id="total-agendamentos">0</div>
                            <div class="stat-label">Total de Agendamentos</div>
                        </div>
                        <div class="stat-card">
                            <div class="stat-number" id="agendamentos-pendentes">0</div>
                            <div class="stat-label">Agendamentos Pendentes</div>
                        </div>
                        <div class="stat-card">
                            <div class="stat-number" id="agendamentos-concluidos">0</div>
                            <div class="stat-label">Agendamentos Concluídos</div>
                        </div>
                    </div>
                    <table class="admin-table">
                        <thead>
                            <tr>
                                <th>Data</th>
                                <th>Cliente</th>
                                <th>Telefone</th>
                                <th>Serviço</th>
                                <th>Tipo</th>
                                <th>Status</th>
                                <th>Ações</th>
                            </tr>
                        </thead>
                        <tbody id="agendamentos-list">
                            <!-- Os agendamentos serão inseridos aqui -->
                        </tbody>
                    </table>
                </div>
                
                <div id="logs-tab" class="tab-content">
                    <h3>Registro de Acessos</h3>
                    <table class="admin-table">
                        <thead>
                            <tr>
                                <th>Data/Hora</th>
                                <th>Usuário</th>
                                <th>Ação</th>
                                <th>Detalhes</th>
                            </tr>
                        </thead>
                        <tbody id="logs-list">
                            <!-- Os logs serão inseridos aqui -->
                        </tbody>
                    </table>
                </div>
                
                <div id="estatisticas-tab" class="tab-content">
                    <h3>Estatísticas do Sistema</h3>
                    <div class="stats-cards">
                        <div class="stat-card">
                            <div class="stat-number" id="total-agendamentos-stats">0</div>
                            <div class="stat-label">Total de Agendamentos</div>
                        </div>
                        <div class="stat-card">
                            <div class="stat-number" id="agendamentos-pendentes-stats">0</div>
                            <div class="stat-label">Agendamentos Pendentes</div>
                        </div>
                        <div class="stat-card">
                            <div class="stat-number" id="agendamentos-concluidos-stats">0</div>
                            <div class="stat-label">Agendamentos Concluídos</div>
                        </div>
                        <div class="stat-card">
                            <div class="stat-number" id="total-acessos">0</div>
                            <div class="stat-label">Total de Acessos</div>
                        </div>
                    </div>
                    
                    <div class="chart-container">
                        <h4>Tipos de Serviços Mais Solicitados</h4>
                        <table class="admin-table">
                            <thead>
                                <tr>
                                    <th>Tipo de Serviço</th>
                                    <th>Quantidade</th>
                                    <th>Percentual</th>
                                </tr>
                            </thead>
                            <tbody id="servicos-stats">
                                <!-- As estatísticas de serviços serão inseridas aqui -->
                            </tbody>
                        </table>
                    </div>
                </div>
                
                <div id="backup-tab" class="tab-content">
                    <h3>Backup e Exportação</h3>
                    <div class="backup-section">
                        <h4>Exportar Dados</h4>
                        <p>Faça backup de todos os agendamentos e dados do sistema.</p>
                        <button class="btn" onclick="exportarDados()">
                            <i class="fas fa-download"></i> Exportar para Excel
                        </button>
                        <button class="btn" onclick="exportarJSON()">
                            <i class="fas fa-file-code"></i> Exportar para JSON
                        </button>
                    </div>
                    
                    <div class="backup-section">
                        <h4>Importar Dados</h4>
                        <p>Restaurar dados de backup anterior.</p>
                        <input type="file" id="import-file" accept=".json,.xlsx" style="margin-bottom: 1rem;">
                        <button class="btn" onclick="importarDados()">
                            <i class="fas fa-upload"></i> Importar Dados
                        </button>
                    </div>
                </div>
            </div>
        </div>
    </div>

    <!-- Notificações -->
    <div id="notification" class="notification"></div>

    <!-- Scripts -->
    <script src="https://cdnjs.cloudflare.com/ajax/libs/jquery/3.6.0/jquery.min.js"></script>
    <script src="https://cdnjs.cloudflare.com/ajax/libs/OwlCarousel2/2.3.4/owl.carousel.min.js"></script>
    <script src="https://cdnjs.cloudflare.com/ajax/libs/xlsx/0.18.5/xlsx.full.min.js"></script>
    
    <script>
        // [Todo o JavaScript do código anterior permanece aqui]
        // Incluindo todas as funções de administração, formulários, etc.
    </script>
</body>
</html>
