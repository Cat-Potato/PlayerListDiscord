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
# Is the plugin enabled
IsEnabled: true
# Debug mode
Debug: false
# Discord bot token
BotToken: Your_Discord_Bot_Token
# Discord channel ID
ChannelId: 123456789012345678
# Discord message ID (if existing)
DiscordMessageId: 0
# Server name
NameServer: "Your Server Name"
# Label for the player list
Player: "Players:"
# Maximum number of players on the server
MaxPlayers: 30
# Player list refresh interval (in ms)
Refreshing: 10000
```  

## Autor  

Plugin stworzony przez **Potato Cat**.  

