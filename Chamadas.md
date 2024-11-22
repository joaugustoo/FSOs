## Chamadas de Sistema

Chamadas de sistema são **interfaces entre programas de usuário e o kernel do SO**. Elas permitem que aplicativos solicitem serviços do sistema operacional, como:

### **Gerenciamento de Arquivos**
- `open()`, `read()`, `write()`, `close()`.

### **Gerenciamento de Processos**
- `fork()`, `exec()`, `exit()`.

### **Comunicação**
- `pipe()`, `shmget()`, `socket()`.

### **Controle de Dispositivos**
- `ioctl()`, `mmap()`.

Essas chamadas variam entre sistemas, mas seguem conceitos comuns.
