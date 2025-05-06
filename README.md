# landing
<!DOCTYPE html>
<html lang="sr">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Prozornica - Kreativne Radionice za Decu</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      background-color: #fff9f2;
      color: #333;
      margin: 0;
      padding: 0;
    }

    header {
      background-color: #f26522;
      color: white;
      text-align: center;
      padding: 2rem 1rem;
    }

    header h1 {
      font-family: 'Baloo 2', cursive;
      font-size: 3rem;
      margin: 0;
    }

    section {
      padding: 2rem 1rem;
    }

    h2 {
      font-size: 2rem;
      color: #f26522;
    }

    p {
      font-size: 1.2rem;
      line-height: 1.6;
    }

    .program-cards {
      display: flex;
      justify-content: space-around;
      gap: 2rem;
      flex-wrap: wrap;
      padding: 1rem;
    }

    .program-card {
      background-color: #ffffff;
      border-radius: 12px;
      padding: 2rem;
      text-align: center;
      width: 250px;
      box-shadow: 0 4px 20px rgba(0, 0, 0, 0.1);
      transition: transform 0.3s ease-in-out, box-shadow 0.3s ease;
    }

    .program-card img {
      width: 60px;
      margin-bottom: 1rem;
    }

    .program-card h3 {
      font-size: 1.4rem;
      color: #f26522;
      margin-bottom: 1rem;
    }

    .program-card p {
      font-size: 1.1rem;
      color: #333;
    }

    .program-card:hover {
      transform: translateY(-10px);
      box-shadow: 0 8px 40px rgba(0, 0, 0, 0.15);
    }

    .program-card img {
      animation: bounce 1s infinite alternate;
    }

    @keyframes bounce {
      0% { transform: translateY(0); }
      100% { transform: translateY(-10px); }
    }

    .contact-info {
      text-align: center;
      margin-top: 2rem;
    }

    .contact-info a {
      color: #f26522;
      text-decoration: none;
      font-weight: bold;
    }
  </style>
</head>
<body>

  <header>
    <h1>Prozornica - Kreativne Radionice za Decu</h1>
  </header>

  <section>
    <h2>Naš cilj:</h2>
    <p>
      Omogućiti deci da se razvijaju kroz inovativne, edukativne aktivnosti, koje uključuju:
    </p>
    <div class="program-cards">
      <div class="program-card">
        <img src="https://i.imgur.com/Hiv5xOG.jpeg" alt="Pisanje sastava" />
        <h3>Pisanje sastava</h3>
        <p>Razvijamo kreativno pisanje i kritičko mišljenje kroz zabavne i angažovane aktivnosti.</p>
      </div>
      <div class="program-card">
        <img src="https://i.imgur.com/N9xea54.jpeg" alt="Logopedske vežbe" />
        <h3>Logopedske vežbe</h3>
        <p>Razvijanje govora i jezika kroz igru i vežbe, sa ciljem poboljšanja izgovora i komunikacije.</p>
      </div>
      <div class="program-card">
        <img src="https://i.imgur.com/jcp2lwL.jpeg" alt="Lutkarsko pozorište" />
        <h3>Lutkarsko pozorište</h3>
        <p>Kreativno izražavanje i razvoj socijalnih veština kroz igru lutkarskog pozorišta.</p>
      </div>
      <div class="program-card">
        <img src="https://i.imgur.com/92iVoxK.jpeg" alt="Relax Kids" />
        <h3>Relax Kids</h3>
        <p>Program opuštanja i samopomoći za decu, zasnovan na meditaciji, disanju i igri.</p>
      </div>
    </div>

    <h2>Zašto Prozornica?</h2>
    <p>
      Naš centar je mesto gde se deca ne samo uče, već se i inspirišu da postanu najbolja verzija sebe. Kroz interaktivne i zabavne metode učenja, pružamo im alatke za rast, izražavanje i rešavanje problema.
    </p>
    
    <div class="contact-info">
      <h3>Kontaktirajte nas!</h3>
      <p>📞 <strong>Telefon:</strong> 0643722673</p>
      <p>📍 <strong>Adresa:</strong> Kosovska BB, Vranje, Srbija</p>
      <p>
        Pratite nas na društvenim mrežama za najnovije informacije i prijavite se za besplatnu probnu radionicu!
      </p>
      <a href="mailto:prozorica@example.com">Pošaljite email</a>
    </div>
  </section>

</body>
</html>
