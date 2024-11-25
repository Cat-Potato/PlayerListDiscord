# PlayerListDiscord Plugin  

[🇬🇧 English](#english) | [🇵🇱 Polski](#polski)  

---

## 🇬🇧 English  

A plugin for SCP: Secret Laboratory that integrates the player list with Discord, updating the information in real time.  

### Features  

- Displays the current player list on a specified Discord channel.  
- Automatic updates at configurable intervals.  
- Handles Discord messages (creates a new message or updates an existing one).  
- Easy configuration management.  

### Requirements  

- SCP: Secret Laboratory server with Exiled API.  
- A Discord bot with appropriate permissions (send messages, embed content).  
- Discord bot token.  
- DSharpPlus library.  

### Installation  

1. Download the latest version of the plugin from [Releases](#).  
2. Copy the DLL file to the `dependencies` folder on your server.  
3. Ensure the configuration file is properly set up.  

### Configuration  

Example configuration file:  

```yaml
IsEnabled: true
Debug: false
BotToken: Your_Discord_Bot_Token
ChannelId: 123456789012345678
DiscordMessageId: 0
NameServer: "Your Server Name"
Player: "Players:"
MaxPlayers: 30
Refreshing: 10000
```  

### How to Use  

1. Enable the plugin on your SCP: Secret Laboratory server.  
2. Ensure your Discord bot is online.  
3. Check the specified Discord channel for the updated player list.  

### Troubleshooting  

If you encounter issues:  
- Verify that your bot token and channel ID are correct.  
- Enable debug mode (`Debug: true`) in the configuration for detailed logs.  

### Author  

Plugin created by **Potato Cat**.  

---

Hosting by Potato Cat.  

---

## 🇵🇱 Polski  

Plugin do SCP: Secret Laboratory, który integruje listę graczy z Discordem, aktualizując informacje w czasie rzeczywistym.  

### Funkcje  

- Wyświetlanie aktualnej listy graczy na określonym kanale Discord.  
- Automatyczna aktualizacja co skonfigurowany czas.  
- Obsługa wiadomości Discord (tworzenie nowej lub aktualizacja istniejącej).  
- Łatwe zarządzanie konfiguracją.  

### Wymagania  

- Serwer SCP: Secret Laboratory z Exiled API.  
- Bot Discord z odpowiednimi uprawnieniami (wysyłanie wiadomości, osadzanie treści).  
- Token bota Discord.  
- Biblioteka DSharpPlus.  

### Instalacja  

1. Pobierz najnowszą wersję wtyczki z [Releases](#).  
2. Skopiuj plik DLL do folderu `dependencies` na swoim serwerze.  
3. Upewnij się, że plik konfiguracyjny jest poprawnie ustawiony.  

### Konfiguracja  

Przykładowy plik konfiguracyjny:  

```yaml
IsEnabled: true
Debug: false
BotToken: Twój_Discord_Bot_Token
ChannelId: 123456789012345678
DiscordMessageId: 0
NameServer: "Nazwa Twojego Serwera"
Player: "Gracze:"
MaxPlayers: 30
Refreshing: 10000
```  

### Jak używać  

1. Włącz plugin na serwerze SCP: Secret Laboratory.  
2. Upewnij się, że bot Discord jest online.  
3. Sprawdź na wskazanym kanale Discord aktualizowaną listę graczy.  

### Problemy i debugowanie  

Jeśli napotkasz problemy:  
- Upewnij się, że token bota i ID kanału są poprawne.  
- Włącz tryb debugowania (`Debug: true`) w konfiguracji, aby uzyskać więcej informacji w logach.  

### Autor  

Plugin stworzony przez **Potato Cat**.  

---

Hosting by Potato Cat.  
