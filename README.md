# Kamihikouki 紙飛行機
A multi downloader tool written in Python.  
Please join [my Discord server](https://discord.gg/2WGqT7B).

### Features
- CLI support.
- Base64 URL input.
- Download in batch from text file.
- Max path length exceedance handling for Windows.
- For those who don't like using the CLI: URL input via the console.
- Filename stripping of unsupported characters in accordance to the user's OS.
- Already existing filename handling. `file.flac -> file (2).flac`, `file (2).flac -> file (3).flac`

### Supported Hosts
| Host  | Info | Author |
| ------------- | ------------- | ------------- 
| clyp.it | Single & user tracks. | Sorrow446
| dbree.org | - | Sorrow446
| ddl.to | Custom captcha solver. | Sorrow446
| gfycat.com | Single & user videos. Quality options. | Sorrow446
| soundgasm.net | Single & user tracks. | Sorrow446
| theartistunion.com | Single tracks. User tracks support soon. No account req. | Sorrow446
| video.9tsu.com | Single videos. User page support soon. | Sorrow446
| wetransfer.com | No agreement req. | Sorrow446
| zippyshare.com | - | Sorrow446

### In Development
| Host  | Info | Author |
| ------------- | ------------- | ------------- 
| real-debrid.com | Single files or folders. Account req. | Sorrow446
| soundcloud.com | Single & user tracks. Attachments by choice. | Sorrow446

# Usage 
Whenever you use this tool via the CLI, you must CD into its directory. It won't be able to read your config file otherwise.

Configure your config file if needed.  
#### Download from a single URL
- Option 1:  
Launch the tool and input URL.
- Option 2:  
Call the tool via the CLI:
``` KAMIHIKOUKI --url <url>```  

#### Download from multiple URLs
Populate a text file with your URLs (one per line).
- Option 1:  
Drag the text file onto the tool.
- Option 2:  
Pass the text file's filename via the CLI:
``` KAMIHIKOUKI <text_file>```  

# Disclaimer
I will not be responsible for how you use this tool.  
This tool has no partnership, sponsorship or endorsement with any of the supported hosts.
