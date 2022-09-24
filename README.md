# ilkwebprojem
Front-End ile Açtığım İlk Repo



<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="css/bootstrap.min.css">
    <title>Careerplan</title>
    <style>



    </style>
</head>

<body>

    <div class="row">
        <div class="container-fluid col-md-12">
            <div class="alert alert-warning alert-dismissible" style="text-align: center;">
                <button type="button" class="close" data-dismiss="alert">&times;</button>
                <strong>Hoşgeldin !!!</strong><br>
                <p>Neden hayatını erteleyeceksin ki sende kariyerini geliştirmeye <a href="https://www.bracket.com.tr/"
                        target="_blank"> başla.</a></p>
            </div>
        </div>
    </div>



    <!--Üst menümüz-->

    <div class="jumbotron text-center" style="margin-bottom:0">
        <h1>Kariyer Planlaması ve Kendini Geliştirmeye Hazır Mısın</h1>
        <p>Kariyer planı; becerilerini, ilgi alanlarını ve kariyer hedefleri belirlemene yardımcı olacak eylemleri
            gerçekleştirmenize olanak tanıyan pratik bir stratejidir.</p>
    </div>

    <nav class="navbar navbar-expand-sm bg-dark navbar-dark sticky-top">
        <a class="navbar-brand" href="#">Anasayfa</a>
        <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#collapsibleNavbar">
            <span class="navbar-toggler-icon"></span>
        </button>
        <div class="collapse navbar-collapse" id="collapsibleNavbar">
            <ul class="navbar-nav">
                <li class="nav-item">
                    <a class="nav-link" href="#">Yazılım</a>
                </li>

                <li class="nav-item">
                    <a class="nav-link" href="#">İşletme</a>
                </li>
                <li class="nav-item">
                    <a class="nav-link" href="#">Finans ve Muhasebe</a>
                </li>
                <li class="nav-item">
                    <a class="nav-link" href="#">Sağlık ve Fitnees</a>
                </li>

                <li class="nav-item">
                    <a class="nav-link" href="#">Tasarım</a>

                </li>
                <li class="nav-item">
                    <a class="nav-link" href="#">Müzik</a>
                </li>
                <li class="nav-item">
                    <a class="nav-link" href="#">Yemek</a>
                </li>
                <li class="nav-item">
                    <a class="nav-link" href="#">Fotoğraf ve Video</a>
                </li>


            </ul>

        </div>
        <form class="form-inline"
            action=https://www.google.com/webhp?hl=tr&sa=X&ved=0ahUKEwiOyrnSuKr6AhWYSvEDHdP9C38QPAgI>
            <input class="form-control mr-sm-2" style="text-align: center;" type="text"
                placeholder="Nasıl yardımcı olalım ?">
            <button class="btn btn-success" type="submit">Ara</button>
        </form>
    </nav>


    <div class="row">
        <div class="container-fluid col-md-6">
            <div id="demo" class="carousel slide" data-ride="carousel">

                <!-- slide listesi -->

                <ul class="carousel-indicators">
                    <li data-target="#demo" data-slide-to="0" class="active"></li>
                    <li data-target="#demo" data-slide-to="1"></li>
                    <li data-target="#demo" data-slide-to="2"></li>
                </ul>

                <!-- slide fotoğrafları -->

                <div class="carousel-inner">
                    <div class="carousel-item active">
                        <img src="image/tasarım.jpg" alt="Los Angeles" style="height: 400px; width: 900px;">
                    </div>
                    <div class="carousel-item">
                        <img src="image/işletme.jpg" alt="Chicago" style="height: 400px; width: 900px;">
                    </div>
                    <div class="carousel-item">
                        <img src="image/finans ve muhasebe.jpg" alt="New York" style="height: 400px; width: 900px;">
                    </div>
                    <div class="carousel-item">
                        <img src="image/yazilim.jpg" alt="Chicago" style="height: 400px; width: 900px;">
                    </div>
                    <div class="carousel-item">
                        <img src="image/fotograf.jpg" alt="Chicago" style="height: 400px; width: 800px;">
                    </div>
                    <div class="carousel-item">
                        <img src="image/yemekk.jpg" alt="Chicago" style="height: 400px; width: 800px;">
                    </div>
                </div>


                <!-- Sol ve Sağ kontrol -->

                <a class="carousel-control-prev" href="#demo" data-slide="prev">
                    <span class="carousel-control-prev-icon"></span>
                </a>
                <a class="carousel-control-next" href="#demo" data-slide="next">
                    <span class="carousel-control-next-icon"></span>
                </a>

            </div>
        </div>

        <!--Card yapısı ve Duyurular Kısmı-->

        <div class="col-md-4 mr-1 text-center">
            <div class="card text-warning bg-info  mb-3 mr-5 mt-3" style="text-align: center;">
                <div class="card-header "><br>
                    <h3>DUYURU ! ! ! </h3>
                </div>
                <div class="card-body">
                    <h5 class="card-title text-dark">BOOTCAMP BAŞVURULARI BAŞLADI</h5>
                    <p class="card-text text-white"> Teknoloji her geçen gün gelişmeye devam ediyor. Bilişim sektöründe
                        gün
                        geçmesin ki yeni bir haber duymayalım. Yazılım ise artık hem günümüzün hem
                        de geleceğin en domine mesleği oldu. Önümüzdeki on yıllar boyunca insanlar yazılımdan çok fazla
                        yararlanacak.İnsanların bu yazılıma evrilme sürecinde ise
                        özellikle günümüzde bootcamp'ler önemli bir yere sahip.</p>
                </div>

            </div>
            <button type="button" class="btn btn-lg btn-danger" data-toggle="popover" data-placement="bottom"
                title="Başvuru Duyurusu   ! ! !"
                data-content="Tüm değerlendirme süreçlerinden geçen adaylar bootcamp'e kabul edilecektir. 6-8 hafta süren bootcamp sürecinde yoğun bir teknik eğitim veriliyor.Adaylardan haftada 30-40 saat vermelerini, tüm ödevleri ve projeleri tamamlaması gerekmektedir.">Sende
                Bootcampe bavur</button>
        </div>


    </div>



    <!--Fotoğraf ve buton ekleme-->

    <div class="row" style="text-align: center;">

        <div class="container col-md-3 "> <br>

            <img src="image/html5.jpg" alt="Html5" style="width:150 ; height: 150px;"><br><br>



            <button type="button" class="btn btn-info btn-lg">HTML 5</button>
        </div>

        <div class="container col-md-3"><br>

            <img src="image/css3.jpg" alt="css" style="width:150 ; height: 150px;"><br><br>



            <button type="button" class="btn btn-info btn-lg">CSS3</button>
        </div>

        <div class="container col-md-3"><br>

            <img src="image/boot.jpg" alt="Html5" style="width:100 ; height: 150px;"><br><br>


            <button type="button" class="btn btn-info btn-lg">Bootstrap</button>
        </div>
        <div class="container col-md-3"><br>

            <img src="image/java.jpg" alt="Html5" style="width:100 ; height: 150px;"><br><br>


            <button type="button" class="btn btn-info btn-lg">JavaScript</button>
        </div>


    </div>











    <div class="container" style="margin-top:30px">
        <div class="row">
            
        </div>
    </div>



    <div class="row">

        <div class="col-md-4 text-center">
            <h2>About Me</h2>
            <h5>Photo of me:</h5>
            <div class="fakeimg">Fake Image</div>
            <p>Some text about me in culpa qui officia deserunt mollit anim..</p>
            <h3>Some Links</h3>
            <p>Lorem ipsum dolor sit ame.</p>
            <ul class="nav nav-pills flex-column">
                <li class="nav-item">
                    <a class="nav-link active" href="#">Active</a>
                </li>
                <li class="nav-item">
                    <a class="nav-link" href="#">Link</a>
                </li>
                <li class="nav-item">
                    <a class="nav-link" href="#">Link</a>
                </li>
                <li class="nav-item">
                    <a class="nav-link disabled" href="#">Disabled</a>
                </li>
            </ul>
            <hr class="d-sm-none">
        </div>
        <div class="col-md-4">
            <h2>TITLE HEADING</h2>
            <h5>Title description, Dec 7, 2017</h5>
            <div class="fakeimg">Fake Image</div>
            <p>Some text..</p>
            <p>Sunt in culpa qui officia deserunt mollit anim id est laborum consectetur adipiscing elit, sed do
                eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud
                exercitation ullamco.</p>
            <br>
            <h2>TITLE HEADING</h2>
            <h5>Title description, Sep 2, 2017</h5>
            <div class="fakeimg">Fake Image</div>
            <p>Some text..</p>
            <p>Sunt in culpa qui officia deserunt mollit anim id est laborum consectetur adipiscing elit, sed do
                eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud
                exercitation ullamco.</p>
        </div>



        <div class="container col-md-3 mr-1 bg-dark text-center">

            <iframe class="embed-responsive-item mr-5 ml-5 mt-2"
                src="https://www.youtube.com/embed/ynZR1R9qhY8"></iframe>

            <iframe class="embed-responsive-item mr-5 ml-5 mt-2"
                src="https://www.youtube.com/embed/oN_8J6W8iJE"></iframe>

            <iframe class="embed-responsive-item mr-5 ml-5 mt-2"
                src="https://www.youtube.com/embed/1-QxqEkbnxo"></iframe>

            <iframe class="embed-responsive-item mr-5 ml-5 mb-2"
                src="https://www.youtube.com/embed/TrstK74pXNY"></iframe>

        </div>


    </div>



    <div class="col-md-6">
        <div class="progress">
            <div class="progress-bar" style="width: 25%" aria-valuenow="25" aria-valuemin="0" aria-valuemax="100">
                %25
            </div>
        </div>

    </div><br><br>


    <div class="jumbotron text-center" style="margin-bottom:0">
        <p>Footer</p>
    </div>








    <script src="js/jquery-3.3.1.min.js"></script>
    <script src="js/popper.min.js"></script>
    <script src="js/bootstrap.min.js"></script>
    <script>
        $(document).ready(function () {
            $('[data-toggle="popover"]').popover();
        });
    </script>

</body>

</html>
