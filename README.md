# MauiMultiTrigger
Project to reproduce possible MAUI error regarding MultiTriggers

## Steps to reproduce
1. Run project and type 999 into the entry field.
   => Program hangs and memory usage increases indefinitely.
2. Comment out the second MultiTrigger Setter and run once more.
   => Program runs as expected (button is disabled).

I'm new to MultiTriggers, so I might be doing something wrong here. If so, please let me know.
