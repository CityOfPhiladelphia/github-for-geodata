Web Proxy
=========

If you're getting an error telling you to check your internet connection, you probably need to set your web proxy for Git. Here's how you do it:

1. Find your .gitconfig file, which should be in `C:\Users\your.username\.gitconfig`
2. Right click file, select “Open With” and find your Notepad program
3. Add the following to this file, replacing "your.username" and "password" with your City of Philadelphia or other network login info:
    
    ```
    [http]
    proxy = http://your.username:password@webproxy.phila.gov:8080
    [https]
    proxy = https://your.username:password@webproxy.phila.gov:8080
    ```

4. Save file
5. Reopen GitHub for Windows and try to clone the repo again

If this doesn't work, get in touch with Patrick.Hammons@phila.gov and we'll try to figure it out!

