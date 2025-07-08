#!/bin/bash

System.out.println("Iniciando perfil de usuário...");

String nome = "Jhonata Henrique Costa Partica";
String alias = "Jhow";
String profissao = "Estudante de Análise e Desenvolvimento de Sistemas";
String linguagemPrincipal = "Java";
String[] linguagens = {"Java", "Python", "Shell Script", "HTML/CSS", "SQL"};
String[] hobbies = {"Programar", "Ouvir música", "Correr", "Assistir séries"};
String[] artistasFavoritos = {"Mac Miller", "Matuê", "BK'", "Veigh", "Teto"};

System.out.println("👋 Olá, eu sou " + alias + "!");
System.out.println("📘 Atualmente curso: " + profissao);
System.out.println("💻 Linguagens que estudo/utilizo:");

for(String l : linguagens){
System.out.println(" - " + l);
}

System.out.println("\n🎧 Artistas que escuto enquanto codifico:");
for(String artista : artistasFavoritos){
System.out.println(" - " + artista);
}

System.out.println("\n🏃‍♂️ Hobbies:");
for(String hobby : hobbies){
System.out.println(" - " + hobby);
}

System.out.println("\n🔧 Conhecimentos adicionais:");
System.out.println(" - POO: Herança, Polimorfismo, Override, Overload");
System.out.println(" - Git/GitHub para versionamento de código");
System.out.println(" - Desenvolvimento de projetos acadêmicos com foco em organização e boas práticas");

System.out.println("\n📈 Atividade no GitHub:");
System.out.println(" - Veja meus commits, contribuições e evolução abaixo:");
System.out.println(" https://github.com/Jhowzzz/github-readme-activity-graph");

System.out.println("\nObrigado por visitar meu perfil. 🚀");
