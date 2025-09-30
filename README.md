# 💬 Cliente TCP em Java (Swing + Sockets)

Este projeto implementa um **cliente TCP simples em Java**, que permite ao usuário enviar mensagens para um servidor via interface gráfica (`JOptionPane`). As mensagens são enviadas por meio de uma conexão socket à porta `4444`.

> Este cliente é ideal para testes com servidores TCP, estudos de redes e programação socket em Java.

## 📌 Funcionalidades

- Conexão a um servidor TCP via IP e porta.
- Interface gráfica para envio de mensagens.
- Envio contínuo de mensagens até digitar "fim".
- Uso de `Socket`, `PrintWriter` e `JOptionPane`.

## 🧠 Como funciona?

- O cliente tenta se conectar ao servidor na porta `4444` (por padrão, em `localhost`).
- Uma caixa de diálogo (`JOptionPane`) é exibida para o usuário digitar mensagens.
- As mensagens são enviadas para o servidor via socket.
- O envio termina quando o usuário digita `fim`.

https://github.com/IgorMirandolli/exemplo_socket_servidor.git
