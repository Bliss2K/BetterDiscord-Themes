### This is in very early development and requires PTB/Canary versions of Discord to work.
**Q**: What are the differences?  
**A**: This version uses the new `backdrop-filter` css rule. Meaning it *should* run faster and the theme wouldn't need to load up to 5 images at once (Non blurred, serverlist, channel list, chat/members list, popout/modal). I'm also trying to use the inbuilt CSS variables to reduce code size.