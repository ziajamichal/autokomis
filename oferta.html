<!DOCTYPE html>
<html lang="pl">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Auto Komis</title>
    <link rel="stylesheet" href="style.css">
    <link rel="shortcut icon" href="logo.jpg" type="image/x-icon">
</head>

<body>
    <header>
        <div class="header-content">
            <!-- Logo w lewym górnym rogu -->
            <div class="logo-container">
                <img src="logo.jpg" alt="Logo" class="logo">
            </div>
            <div class="header-text">
                <h1>Caro Strefa</h1>
                <p>Znajdź swój wymarzony samochód w CaroStrefa!</p>
                <div class="contact-info">
                    <p class="phone-number">
                        <span>+48 092 902 291</span>
                        <span class="call-option">Zadzwoń</span>
                    </p>
                </div>
            </div>

            <!-- Menu nawigacyjne -->
            <nav>
                <ul class="nav-menu">
                <li><a href="index.html">O nas</a></li>
                    <li><a href="oferta.php">Oferta</a></li>
                    <li><a href="social.html">Social Media</a></li>
                    <li><a href="kontakt.html">Kontakt</a></li>
                </ul>
            </nav>
    </header><br>
    <section class="alert-box">
    <h3><img src="uwaga.png" alt="">     Uwaga</h3>
    
    <p> Ta oferta jest przykładem z naszej oferty i nie jesteśmy właścicielami tych pojazdów. Samochody te są wzięte z darmowej, nieobjętej prawami autorskimi grafiki.</p>
    </section>
    <section id="container">
        <h4>Oferta Dnia</h4>
    <section id="blok1">
    
        <?php
        $polaczenie = mysqli_connect("localhost", "root", "", "kupauto");

        if (!$polaczenie) {
            die("Błąd połączenia: " . mysqli_connect_error());
        }
        else{
            $zapytanie = "SELECT model, rocznik, przebieg, paliwo, cena, zdjecie FROM samochody WHERE id = 10;";
            $wynik = mysqli_query($polaczenie, $zapytanie);
            while ($row = mysqli_fetch_array  ($wynik))
        {
        echo "<img src='".$row['zdjecie']."' alt='oferta dnia'>";
        echo "<h4> Toyota " .$row['model']."</h4>";
        echo "<h1>Rocznik:".$row['rocznik']."</h1>";
        echo "<h1>Rocznik:".$row['przebieg']."</h1>";
        echo "<h1>Paliwo:".$row['paliwo']."</h1>";
        echo "<h4>Cena: " .$row['cena']."</h4>";
        }
        }
        ?>
    </section>
    
    <section id="blok2">
        <h2>Oferty Wyróżnione</h2>
        <?php
         $zapytanie = "SELECT nazwa, model, rocznik,przebieg, paliwo, cena, zdjecie FROM marki JOIN samochody ON marki.id = samochody.marki_id WHERE samochody.wyrozniony = '1' LIMIT 4";
         $wynik = mysqli_query($polaczenie, $zapytanie);
         while ($row = mysqli_fetch_array  ($wynik))
        {
            echo "<section class='blok4'>";
        echo "<img src='".$row['zdjecie']."' alt='model'>";
        echo "<h3>".$row['nazwa']." ".$row['model']."</h3>";
        echo "<p>Rocznik:".$row['rocznik']."</p>";
        echo "<p>Rocznik:".$row['przebieg']."</p>";
        echo "<p>Paliwo:".$row['paliwo']."</p>";
        echo "<h3>Cena: " .$row['cena']."</h3>";
        echo "</section>";
        }
        ?>
    </section>
        <section id="blok3">
            <h2>Wybierz markę</h2>
            <form action="" method="post">
                <select name="wybor">
                    <?php
                    $zapytanie = "SELECT nazwa FROM marki";
                    $wynik = mysqli_query($polaczenie, $zapytanie);
                    while ($row = mysqli_fetch_array  ($wynik))
                {
                    echo "<option>".$row['nazwa']."</option>";
                }
                    ?>
                </select>
                <button name="wyszukaj">Wyszukaj</button><br>
                <?php

                if(isset($_POST['wyszukaj'])){

                    $wybor = $_POST['wybor'];


                $zapytanie = "SELECT model, rocznik,przebieg, paliwo, cena, zdjecie, nazwa FROM samochody JOIN marki ON marki_id = marki.id WHERE marki.nazwa = '$wybor';";
                $wynik = mysqli_query($polaczenie, $zapytanie);
                while ($row = mysqli_fetch_array  ($wynik))
            {
                echo "<section class='blok4'>";
                echo "<img src='".$row['zdjecie']."' alt='model'>";
            echo "<h3>".$row['nazwa']." ".$row['model']."</h3>";
            echo "<p>Rocznik:".$row['rocznik']."</p>";
            echo "<p>Rocznik:".$row['przebieg']."</p>";
            echo "<p>Paliwo:".$row['paliwo']."</p>";
            echo "<h3>Cena: " .$row['cena']."</h3>";
            echo "</section>";
            }
                }
            mysqli_close($polaczenie);
                ?>
            </form>
        </section>
    </section>
    <footer>
        <div class="footer-content">
            <div class="footer-info">
                <h3>CaroStrefa</h3>
                <p>Komis Samochodowy w Szymbarku, obok DK28. Znajdź swoje wymarzone auto w atrakcyjnych cenach!</p>
            </div>

            <div class="footer-contact">
                <h4>Dane Kontaktowe</h4>
                <ul>
                    <li>Telefon: <a href="tel:+48691104711">+48 092 902 291</a></li>
                    <li>Email: <a href="mailto:kontakt@carostrefa.pl">kontakt@carostrefa.pl</a></li>
                    <li>Adres: Szymbark 242, 38-311 Szymbark</li>
                </ul>
            </div>

            <div class="footer-social">
                <img src="logo.jpg" alt="">
            </div>
        </div>

        <div class="footer-bottom">
            <p>&copy; CaroStrefa - Wszelkie prawa zastrzeżone.</p>
        </div>
    </footer>
    </body>
</html>

<option></option>
