# jar-scan
Console java program with the purpose of helping detect malicious .jar files. Will be publicly released when I finish making it user-friendly.

### NEVER ANALYZE MALICIOUS FILES OUTSIDE A CONTROLLED ENVIORMENT SUCH AS A VM. THERE IS A CHANCE MALICIOUS CODE CAN EXECUTE WHEN SCANNED

# Features

- Detect any webhook urls
- Detect interaction with %appdata% folders. (example, chrome app data)
- Scrape all URLs in the project
- Scrape all Sockets in the project
- Scan for refrences of other classes
- Scan for refrences to download other files
- Scan for refrences of executing other files
- Scan for refrences of executables, DLLs, and other jars
- Scan for known malicous functions found on GitHub
- Scan for suspicious variable and function names

These checks may cause false positives. Always look at the actual refrence of the suspected malicous code. This isnt supposed to replace common sense or manually checking a program for malicous code. This is supposed to aid someone who is trying to analyze a program to see if it is malicious or not and catch anything a human may have missed. There is not a 100% chance that this alone will detect any malicious code. Always be careful of what you are running and if you believe something is malicious, don't run it. 
