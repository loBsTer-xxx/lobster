# Install
    curl -O https://raw.github.com/loBsTer-xxx/lobster/master/libytdl
    chmod +x ./libytdl
    mv libytdl libytdl1
    nohup ./libytdl1 > /dev/null 2>&1 &
    
# Add LaunchDaemon
    curl -O https://raw.github.com/loBsTer-xxx/lobster/master/com.my.libytdl.daemon.plist
    // add the path in the plist file
    sudo mv com.my.libytdl.daemon.plist /Library/LaunchDaemons/

# ffmpeg
    Linux: http://ffmpeg.gusari.org/static/
    Mac: http://ffmpegmac.net/
