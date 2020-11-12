# ServerMapper
Loads PE image on server and sends ready to use mapped image to client without PE headers and reloc section

UC Thread: https://www.unknowncheats.me/forum/c-and-c-/396513-server-mapper.html

### Ideas to improve the mapper:
- Get rid of PE directory descriptors
- Write sections to mapped image separately to avoid useless sections writing
- Xor encrypt imported functions data

Actually, there're many more ideas to improve PE mapper, but I want to keep it private. Just figure out it yourself, it's not that hard
