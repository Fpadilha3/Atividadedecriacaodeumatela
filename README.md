# 🔐 Tela de Login em Java (Swing + NetBeans)

## 📌 Descrição

Este projeto consiste na criação de uma **tela de login** utilizando **Java com Swing**, desenvolvida no **NetBeans IDE**, com separação em camadas:

* **DTO (Data Transfer Object)** → Armazena os dados do usuário
* **DAO (Data Access Object)** → Responsável pela lógica de autenticação
* **VIEW** → Interface gráfica (tela de login)

---

## 🗂️ Estrutura do Projeto

```
telalogin
 ├── dao
 │    └── UsuarioDAO.java
 ├── dto
 │    └── UsuarioDTO.java
 └── view
      └── LoginTela.java
```

---

## 🛠️ Tecnologias Utilizadas

* Java
* Swing (GUI)
* NetBeans IDE

---

## 🎯 Funcionalidades

✔ Tela de login com interface gráfica
✔ Validação de campos vazios
✔ Autenticação de usuário
✔ Mensagens de erro e sucesso

---

## 🔑 Credenciais de Acesso

Para testar o sistema:

```
Usuário: admin
Senha: 1234
```

---

## ▶️ Como Executar

1. Abra o projeto no NetBeans
2. Execute a classe:

```
view.LoginTela
```

3. Insira as credenciais e clique em **Entrar**

---

## 📷 Funcionamento

* ✅ Login correto:

```
Login realizado com sucesso!
```

* ❌ Login incorreto:

```
Usuário ou senha incorretos!
```

* ⚠ Campos vazios:

```
Preencha todos os campos!
```

---

## 🧠 Lógica do Sistema

### 📄 DTO (UsuarioDTO)

Responsável por armazenar:

* usuário
* senha

---

### 📄 DAO (UsuarioDAO)

Responsável por:

* validar login
* comparar com dados fixos

---

### 📄 VIEW (LoginTela)

Responsável por:

* interface gráfica
* captura de dados
* exibição de mensagens

---

## 💡 Melhorias Futuras

* 🔗 Integração com banco de dados (MySQL)
* 📝 Tela de cadastro de usuários
* 🔒 Criptografia de senha
* 🎨 Interface mais moderna

---

## 👨‍💻 Autor

Projeto desenvolvido para fins acadêmicos.
