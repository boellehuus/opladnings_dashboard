Elbil Ladeplan Dashboard

Kompakt dashboard til visualisering af elpriser og optimal ladeplan for elbiler, optimeret til Homey iOS Dashboard widgets.
🎯 Funktioner

    📊 Elprissøjler med farvekodet prisvisning
    ⚡ Ladeplan markering med animeret mønster
    📅 Historik - Se gårsdagens, dagens og morgendagens priser
    🕐 Realtid - Mørkere farver på forbi timer
    📱 Mobiloptimeret - Perfekt til iOS Dashboard widgets
    🔄 Auto-opdatering - Henter data hver minut fra Homey

🎨 Design

Inspireret af Homey App'ens rene design:

    Hvid baggrund med subtile skygger
    System fonts (SF Pro Display)
    Flade kort uden gradienter
    Prisstigningslinjer hver 0,5 kr
    Homey-farver (grøn for ladning)

🔗 Integration

Dashboard integreres med Homey Pro via:

    HomeyScript læser Tesla variabler
    BilligkWh API henter elpriser (DK1)
    GitHub Gist som webhook endpoint
    HTML Dashboard henter data hver minut

📊 Prisfarvekodning

    🟢 Grøn: < 2,5 kr/kWh (billige priser)
    🟠 Orange: 2,5-3,0 kr/kWh (dyre priser)
    🔴 Rød: 3,0-3,5 kr/kWh (meget dyre)
    🟣 Lilla: > 3,5 kr/kWh (ekstrem dyre)
    ⚡ Animeret grøn: Planlagte ladetimer

🔧 Opsætning

    Konfigurer HomeyScript med GitHub token
    Opret GitHub Gist til data
    Tilføj HTML som web widget i Homey Dashboard
    Script kører automatisk hver 15. minut

📱 iOS Dashboard

Tilføj som Web Widget i Homey iOS app:

    Kompakt layout til small/medium widgets
    Auto-refresh med batterioptimering
    Offline fallback med testdata

Teknologi: HTML5, CSS3, JavaScript, Homey Logic Variables, BilligkWh API
