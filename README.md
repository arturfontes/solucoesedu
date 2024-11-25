<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Soluções Tecnológicas</title>
    <link href="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/css/bootstrap.min.css" rel="stylesheet">
</head>
<body>
    <div class="container" style="max-width: 80%;">
        <h1 class="mt-4 text-center">Soluções Tecnológicas</h1>
        <p class="text-center">Abaixo estão todas as soluções tecnológicas que a Faculdade CENSUPEG disponibiliza para o seu protagonismo.</p>

        <!-- Botão de Busca de Soluções -->
        <div class="text-center mt-3">
            <button class="btn btn-info" data-toggle="modal" data-target="#searchModal">Buscar Soluções</button>
        </div>

        <!-- Modal para Buscar Soluções -->
        <div class="modal fade" id="searchModal" tabindex="-1" aria-labelledby="searchModalLabel" aria-hidden="true">
            <div class="modal-dialog">
                <div class="modal-content">
                    <div class="modal-header">
                        <h5 class="modal-title" id="searchModalLabel">Soluções Disponíveis</h5>
                        <button type="button" class="close" data-dismiss="modal" aria-label="Close">
                            <span aria-hidden="true">&times;</span>
                        </button>
                    </div>
                    <div class="modal-body">
                        <ul>
                            <li><a href="#officeSection" class="text-decoration-none">Office365</a></li>
                            <li><a href="#autodeskSection" class="text-decoration-none">Autodesk</a></li>
                            <li><a href="#jetbrainsSection" class="text-decoration-none">JetBrains</a></li>
                            <li><a href="#awsSection" class="text-decoration-none">AWS</a></li>
                        </ul>
                    </div>
                </div>
            </div>
        </div>

        <div class="row mt-4">
            <!-- Office365 -->
            <div class="col-md-4 mb-4" id="officeSection">
                <div class="card">
                    <img src="office.png" alt="Office 365" class="img-fluid mb-3">
                    <div class="card-body">
                        <h5 class="card-title">Office365</h5>
                        <button class="btn btn-secondary mb-3" onclick="showSolutionsText('officeText')">Soluções Disponíveis</button>
                        <p id="officeText" class="text-muted d-none">Essas são as seguintes soluções que poderá utilizar:
                            <br>Word
                            <br>Excel
                            <br>PowerPoint
                            <br>OneNote
                            <br>Outlook
                            <br>Teams
                            <br>OneDrive
                            <br>SharePoint
                            <br>Forms
                            <br>Stream
                            <br>Sway
                            <br>Planner
                            <br>Yammer
                            <br>Power Automate
                            <br>Power Apps
                            <br>Bookings
                            <br>To Do
                            <br>Whiteboard
                        </p>
                        <button class="btn btn-primary mt-3" type="button" data-toggle="collapse" data-target="#officeInfo" aria-expanded="false" aria-controls="officeInfo">
                            Procedimentos para Obtenção
                        </button>
                        <div class="collapse mt-3" id="officeInfo">
                            <p>Siga os passos abaixo para instalar o Office365 com licença educacional:</p>
                            <ol>
                                <li>Vá até <a href="https://www.office.com" target="_blank">office.com</a> e faça login com seu e-mail @censupeg.</li>
                                <li>Clique em "Instalar o Office" no canto superior direito.</li>
                                <li>Baixe e execute o instalador.</li>
                                <li>Siga as instruções do assistente de instalação para concluir.</li>
                            </ol>
                        </div>
                    </div>
                </div>
            </div>

            <!-- Autodesk -->
            <div class="col-md-4 mb-4" id="autodeskSection">
                <div class="card">
                    <img src="autodesk.png" alt="Autodesk" class="img-fluid mb-3">
                    <div class="card-body">
                        <h5 class="card-title">Autodesk</h5>
                        <button class="btn btn-secondary mb-3" onclick="showSolutionsText('autodeskText')">Soluções Disponíveis</button>
                        <p id="autodeskText" class="text-muted d-none">Essas são as seguintes soluções que poderá utilizar:
                            <br>Tinkercad
                            <br>Fusion 360
                            <br>3ds Max
                            <br>Maya
                            <br>Mudbox
                            <br>MotionBuilder
                            <br>Revit
                            <br>AutoCAD Architecture
                            <br>Civil 3D
                            <br>InfraWorks
                            <br>Navisworks Manage
                            <br>Inventor Professional
                            <br>AutoCAD Mechanical
                            <br>Advance Steel
                            <br>Factory Design Utilities
                            <br>Inventor CAM Ultimate
                            <br>Autodesk CFD Ultimate
                            <br>Inventor Nastran
                            <br>Robot Structural Analysis Professional
                            <br>Structural Bridge Design
                            <br>Autodesk Construction Cloud
                            <br>Cloud Worksharing
                            <br>Vault Professional
                            <br>Flame
                            <br>Arnold
                            <br>VRED Professional
                        </p>
                        <button class="btn btn-primary mt-3" type="button" data-toggle="collapse" data-target="#autodeskInfo" aria-expanded="false" aria-controls="autodeskInfo">
                            Procedimentos para Obtenção
                        </button>
                        <div class="collapse mt-3" id="autodeskInfo">
                            <p>Siga os passos abaixo para instalar os produtos Autodesk com licença educacional:</p>
                            <ol>
                                <li>Acesse o site <a href="https://https://www.autodesk.com/br/education/edu-software/overview" target="_blank">Autodesk Education</a>.</li>
		<li>Selecione o software desejado na listagem</li>
                                <li>Crie uma conta ou faça login com seu e-mail @censupeg.</li>
                                <li>Durante o cadastro, o Autodesk solicitará informações sobre a escola, deverá colocar as seguintes informações.</li>
		<li>Endereço Escolar:</li>
		<br>País: Brasil
		<br>Endereço: Av. Juscelino Kubitscheck, 627
		<br>Cidade: Joinville
		<br>Código postal: 89201-100
		<li>Informações da Escola:</li>
		<br>Tipo de instituição: Universitário/ensino superior
		<br>Nome da instituição educacional: Faculdade Censupeg (Joinville, SC)
		<br>Site da escola: www.censupeg.com.br/academy
                                <li>Siga as instruções até completar a instalação.</li>
                            </ol>
                        </div>
                    </div>
                </div>
            </div>

            <!-- JetBrains -->
            <div class="col-md-4 mb-4" id="jetbrainsSection">
                <div class="card">
                    <img src="jet.png" alt="JetBrains" class="img-fluid mb-3">
                    <div class="card-body">
                        <h5 class="card-title">JetBrains</h5>
                        <button class="btn btn-secondary mb-3" onclick="showSolutionsText('jetbrainsText')">Soluções Disponíveis</button>
                        <p id="jetbrainsText" class="text-muted d-none">Essas são as seguintes soluções que poderá utilizar:
                            <br>IntelliJ IDEA
                            <br>PyCharm
                            <br>PhpStorm
                            <br>WebStorm
                            <br>Rider
                            <br>ReSharper
                            <br>ReSharper C++
                            <br>dotTrace
                            <br>dotMemory
                            <br>dotCover
                            <br>Aqua
                            <br>RustRover
                            <br>YouTrack
                            <br>TeamCity
                            <br>CLion
                            <br>AppCode
                            <br>DataGrip
                            <br>MPS
                        </p>
                        <button class="btn btn-primary mt-3" type="button" data-toggle="collapse" data-target="#jetbrainsInfo" aria-expanded="false" aria-controls="jetbrainsInfo">
                            Procedimentos para Obtenção
                        </button>
                        <div class="collapse mt-3" id="jetbrainsInfo">
                            <p>Siga os passos abaixo para instalar o JetBrains com licença educacional:</p>
                            <ol>
                                <li>Crie uma conta no site <a href="https://https://www.jetbrains.com/shop/eform/students" target="_blank">JetBrains para Educação</a>.</li>
                                <li>Utilize o seu e-mail @censupeg. para a criação de conta</li>
		<li>Acesse seu e-mail @censupeg (webmail.censupeg.com.br ) e confirme a criação de conta</li>
                                <li>Entre novamente na sua conta criada no jetbrains.</li>
                                <li>Terá acesso a área de download de softwares e ao ID da licença.</li>
                            </ol>
                        </div>
                    </div>
                </div>
            </div>

            <!-- AWS Educate -->
            <div class="col-md-4 mb-4" id="awsSection">
                <div class="card">
                    <img src="aws.png" alt="AWS" class="img-fluid mb-3">
                    <div class="card-body">
                        <h5 class="card-title">AWS Educate</h5>
                        <button class="btn btn-secondary mb-3" onclick="showSolutionsText('awsText')">Soluções Disponíveis</button>
                        <p id="awsText" class="text-muted d-none">Essas são as seguintes soluções que poderá utilizar:
                            <br>Amazon EC2
                            <br>Amazon S3
                            <br>Amazon RDS
                            <br>Amazon Lambda
                            <br>Amazon CloudFront
                            <br>Amazon DynamoDB
                            <br>Amazon Rekognition
                            <br>Amazon SageMaker
                            <br>Amazon Aurora
                            <br>Amazon CloudWatch
                            <br>Amazon Redshift
                        </p>
                        <button class="btn btn-primary mt-3" type="button" data-toggle="collapse" data-target="#awsInfo" aria-expanded="false" aria-controls="awsInfo">
                            Procedimentos para Obtenção
                        </button>
                        <div class="collapse mt-3" id="awsInfo">
                            <p>Siga os passos abaixo para utilizar os serviços AWS com acesso educacional:</p>
                            <ol>
                                <li>Acesse o site <a href="https://aws.amazon.com/education/awseducate/" target="_blank">AWS Educate</a>.</li>
                                <li>Crie uma conta utilizando o seu e-mail @censupeg.</li>
                                <li>Preencha as informações solicitadas, incluindo o nome da instituição educacional: "Faculdade Censupeg".</li>
                                <li>Após a aprovação, você terá acesso aos créditos e serviços AWS.</li>
                                <li>Explore a plataforma AWS para ativar e gerenciar os serviços desejados.</li>
                            </ol>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </div>

    <script>
        function showSolutionsText(id) {
            const element = document.getElementById(id);
            element.classList.toggle("d-none");
        }
    </script>
    <script src="https://code.jquery.com/jquery-3.5.1.slim.min.js"></script>
    <script src="https://cdn.jsdelivr.net/npm/@popperjs/core@2.4.4/dist/umd/popper.min.js"></script>
    <script src="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/js/bootstrap.min.js"></script>
</body>
</html># solucoesedu
