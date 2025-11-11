# PDV-FrontEnd-JavaPOO

FrontEnd do meu projeto PDV-Posto-Combustível

## 🚀 Tecnologias

- Java 17
- Java Swing
- Apache HttpClient 5
- Jackson (JSON)
- FlatLaf (Look & Feel moderno)
- Maven

## 📋 Pré-requisitos

- Java JDK 17 ou superior
- Backend rodando em `http://localhost:8080`
- Maven (ou usar o mvnw incluído)

## 🔧 Configuração

1. Clone o repositório:
```bash
git clone https://github.com/Sidney-Emanuel-Oliveira/PDV-FrontEnd-JavaPOO.git
cd PDV-FrontEnd-JavaPOO
```

2. Certifique-se de que o backend está rodando:
   - O backend deve estar disponível em `http://localhost:8080`
   - Veja: [PDV-BackEnd-JavaPOO](https://github.com/Sidney-Emanuel-Oliveira/PDV-BackEnd-JavaPOO)

## ▶️ Como executar

### Opção 1: Via Maven
```bash
mvn clean compile
mvn exec:java -Dexec.mainClass="br.com.PdvFrontEnd.MainApp"
```

### Opção 2: Via Maven Wrapper
```bash
./mvnw clean compile
./mvnw exec:java -Dexec.mainClass="br.com.PdvFrontEnd.MainApp"
```

### Opção 3: Compilar e executar o JAR
```bash
mvn clean package
java -jar target/pdv-frontend-0.0.1-SNAPSHOT.jar
```

## 📱 Funcionalidades

- ✅ Tela de Login
- ✅ Cadastro de Pessoas (Funcionários, Clientes, Fornecedores)
- ✅ Cadastro de Produtos
- ✅ Gestão de Estoque
- ✅ Gestão de Preços
- ✅ Gestão de Custos
- ✅ Controle de Acessos
- ✅ Interface moderna com FlatLaf

## 🔗 Backend

O backend deste projeto está disponível em: [PDV-BackEnd-JavaPOO](https://github.com/Sidney-Emanuel-Oliveira/PDV-BackEnd-JavaPOO)

## 📝 Credenciais padrão

- **Usuário:** admin
- **Senha:** admin123

## 📝 Licença

Este projeto está sob a licença MIT.

