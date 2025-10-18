---
layout: default
title: Strona Główna | Imię i Nazwisko
---

<style>
  /* Dodajemy niestandardowe style dla sekcji */
  .grid-container {
    display: flex;
    justify-content: space-around;
    gap: 30px; /* Odstęp między kwadratami */
    margin-top: 50px;
    flex-wrap: wrap; /* Zapewnia responsywność */
  }

  .grid-item {
    text-align: center;
    text-decoration: none;
    color: white; /* Kolor tekstu dla kontrastu */
    width: 250px; /* Szerokość kwadratu */
    height: 250px; /* Wysokość kwadratu */
    display: flex;
    align-items: center;
    justify-content: center;
    font-size: 24px;
    font-weight: bold;
    border-radius: 10px; /* Zaokrąglone rogi */
    transition: transform 0.3s, box-shadow 0.3s;
  }

  /* Styl dla Gamedev - niebieski */
  .gamedev {
    background-color: #3498db; 
  }

  /* Styl dla Wokal - czerwony/różowy */
  .wokal {
    background-color: #e74c3c;
  }

  /* Efekt najechania myszą */
  .grid-item:hover {
    transform: translateY(-5px); /* Lekkie podniesienie */
    box-shadow: 0 10px 20px rgba(0, 0, 0, 0.2);
  }
</style>

# Cześć! Odkryj moje projekty i pasje.

## O Mnie

Witaj na mojej przestrzeni w sieci! Ta strona to wirtualne portfolio, w którym łączę dwie moje największe pasje: tworzenie gier (Gamedev) i muzykę (Wokal). Znajdziesz tu zarówno techniczne projekty koderskie, jak i twórczość artystyczną.

Zapraszam do eksplorowania!

---

<div class="grid-container">
    <a href="/gamedev/" class="grid-item gamedev">
        GAMEDEV
    </a>
    <a href="/wokal/" class="grid-item wokal">
        WOKAL
    </a>
</div>
