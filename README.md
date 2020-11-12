# ServerMapper
Loads PE image on server and sends ready to use mapped image to client without PE headers and reloc section

UC Thread: https://www.unknowncheats.me/forum/c-and-c-/396513-server-mapper.html

### Ideas to improve the mapper:
- Get rid of PE directory descriptors
- Write sections to mapped image separately to avoid useless sections writing
- Xor encrypt imported functions data

Actually, there're many more ideas to improve PE mapper, but I want to keep them private. Just figure it out yourself, it's not that hard

### Useful literature
- https://www.programmersought.com/article/9651128893/ Information about relocation table, pretty useful
- https://docs.microsoft.com/en-us/windows/win32/debug/pe-format Windows docs, describes descriptors, tables and so on
- https://github.com/corkami/pics 
