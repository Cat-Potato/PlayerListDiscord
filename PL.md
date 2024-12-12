# PlayerListDiscord Plugin  

Plugin do SCP: Secret Laboratory, który integruje listę graczy z Discordem.

## Funkcje  

- Wyświetlanie aktualnej listy graczy na określonym kanale Discord.  
- Automatyczna aktualizacja co skonfigurowany czas.  
- Obsługa wiadomości Discord (tworzenie nowej lub aktualizacja istniejącej).  
- Łatwe zarządzanie konfiguracją.  

## Wymagania  

- Serwer SCP: Secret Laboratory z Exiled API.  
- Bot Discord z odpowiednimi uprawnieniami (wysyłanie wiadomości, osadzanie treści).  
- Token bota Discord.   

## Instalacja  

1. Pobierz najnowszą wersję wtyczki z [Releases](https://github.com/Cat-Potato/PlayerListDiscord/releases).  
2. Skopiuj plik DLL do folderu `Plugins` na swoim serwerze.
3. Pobierz `dependencies.zip` i rozpakuj.
4. Wrzuć do folderu `dependencies`.

## Niekompatybilny
- [DiscordIntegration](https://github.com/Exiled-Team/DiscordIntegration)

## Testerzy
- [Altzheimer Von Cruvez](https://steamcommunity.com/profiles/76561199515830986/)

## Konfiguracja  

Plik konfiguracyjny:  

```yml
playerlist:
  is_enabled: true
  debug: false
  # Auto Update info Plugin:
  update_info: true
  # Bot:
  bot_token: 'Bot_Token'
  channel_id: 1234567890101112131
  discord_message_id: 0
  name_server: 'ServerName'
  player_label: 'Players:'
  # Only HEX color
  embed_color: '#FFFF00'
  no_player: 'No Players :('
  max_players: 30
  # Player list refresh interval (in ms)
  refresh_interval: 10000
  ascii_art: true
```

## Showcase
<img src="preview1.png">

S
