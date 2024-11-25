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
- Biblioteka DSharpPlus.  

## Instalacja  

1. Pobierz najnowszą wersję wtyczki z [Releases](#).  
2. Skopiuj plik DLL do folderu `Plugins` na swoim serwerze.
3. Pobierz `dependencies.zip` i wrzuć do folderu `dependencies`

## Konfiguracja  

Przykładowy plik konfiguracyjny:  

```yaml
playerlist:
  is_enabled: true
  debug: false
  bot_token: 'Discord_Bot_Token'
  channel_id: 123456789012345678
  discord_message_id: 0
  name_server: 'ServerName'
  player_label: 'Players:'
  no_player: 'No Players :('
  max_players: 30
  # Player list refresh interval (in ms)
  refresh_interval: 10000
```  
