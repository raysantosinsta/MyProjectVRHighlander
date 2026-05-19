# 🏛️ PROJETO FINAL — MUSEU HUMANOIDE VR

Um projeto de Realidade Virtual desenvolvido na Unity com foco na aplicação dos fundamentos de XR (Extended Reality), utilizando o Meta XR SDK para criar uma experiência imersiva e educativa baseada em um museu anatômico virtual.

---

# 📖 INTRODUÇÃO

O **Museu Humanoide VR** consiste na criação de um ambiente virtual interativo voltado para exposição de partes do corpo humano em Realidade Virtual.

O projeto foi desenvolvido durante a primeira fase do curso de XR com o objetivo de compreender os fundamentos do desenvolvimento VR dentro da Unity, incluindo:

- ambientação virtual;
- movimentação do usuário;
- interação com objetos;
- configuração de XR;
- build para dispositivos Meta Quest.

O ambiente permite que os usuários explorem o espaço virtual, observem modelos 3D anatômicos e interajam com objetos de forma imersiva.

---

# 🛠️ CONFIGURAÇÃO TÉCNICA

## Tecnologias Utilizadas

- **Motor Gráfico:** Unity `6000.3.16f1`
- **Linguagem:** C#
- **SDK:** Meta XR All-in-One SDK
- **Plataforma Build:** Android (Meta Quest)
- **XR Plugin Management:** Configurado e habilitado
- **Meta XR Simulator:** Ativado para testes diretamente no editor
- **Interaction SDK:** Utilizado para interações VR

---

# ⚙️ FUNCIONALIDADES IMPLEMENTADAS

- ✅ Navegação em ambiente VR utilizando XR Rig;
- ✅ Simulação VR diretamente no computador;
- ✅ Interação com objetos através de Ray Grab Interaction;
- ✅ Ambiente anatômico imersivo;
- ✅ Skybox personalizado;
- ✅ Organização otimizada do projeto;
- ✅ Compatibilidade com Meta Quest.

---

# 🧠 DETALHES DO AMBIENTE VIRTUAL

O cenário foi desenvolvido para simular um pequeno museu anatômico virtual contendo modelos humanos em exposição.

## Estrutura do Cenário

- chão texturizado;
- paredes internas;
- iluminação básica;
- skybox personalizado;
- área de exposição;
- mostruários anatômicos.

---

# 🧍 OBJETOS 3D PRESENTES

## Primeiro Mostruário

- Base preta;
- Caixa de amostragem;
- Modelo de corpo humano.

## Segundo Mostruário

- Base preta secundária;
- Caixa de amostragem secundária;
- Modelo de crânio humano.

## Mesa

- base cinza;

## Cadeira

- base dourada;

## Enfeite Dragão

- partes
- patas, rabo, asa

---

# 🥽 RECURSOS XR UTILIZADOS

## XR Rig + Character Controller

Responsáveis pela movimentação do jogador dentro do ambiente virtual.

## Ray Grab Interaction

Permite pegar e interagir com objetos utilizando os controles VR.

## Meta XR Simulator

Ferramenta utilizada para simular a experiência VR diretamente na Unity sem necessidade imediata do headset.

## Camera Ring (BuildBlock)

Utilizado para auxiliar na delimitação visual da experiência VR.

---

# 📦 PACKAGES UTILIZADOS

O projeto utiliza os seguintes pacotes:

- Meta XR Simulator;
- Meta XR All-in-One SDK;
- Skybox Series Free.

---

# 📁 ESTRUTURA DO PROJETO

```txt
MuseuHumanoideVR
│
├── Assets
├── Packages
│
├── Models
├── Materials
├── Textures
```

---

# 🚀 COMO EXECUTAR O PROJETO

## Pré-requisitos

- Unity Hub instalado;
- Unity versão `6000.3.16f1`;
- Meta Quest Link ou ambiente XR configurado;
- Meta XR SDK instalado.

---

## Passos para Execução

1. Clone este repositório:

```bash
git clone https://github.com/raysantosinsta/MyProjectVRHighlander.git
```

2. Abra o projeto no Unity Hub;

3. Aguarde a importação dos pacotes;

4. Abra a cena principal do projeto;

5. Ative o Meta XR Simulator ou conecte um headset Meta Quest;

6. Clique em **Play** para iniciar a experiência VR.

---

# 🧹 ORGANIZAÇÃO E BOAS PRÁTICAS

O projeto foi estruturado seguindo boas práticas de desenvolvimento Unity:

- organização por categorias;
- nomenclaturas descritivas;
- remoção de arquivos desnecessários;
- separação de assets;
- estrutura limpa para manutenção.

---

# 📚 APRENDIZADOS

Durante o desenvolvimento do projeto, foi possível aprender:

- configuração de ambientes XR;
- integração do Meta XR SDK;
- utilização do XR Rig;
- interações em VR;
- build Android para Meta Quest;
- organização profissional de projetos Unity.

O maior desafio foi configurar corretamente o XR Plugin Management e adaptar o projeto para dispositivos Android/Meta Quest.

---

# 🔗 REPOSITÓRIO

## GitHub

[Museu Humanoide VR Repository](https://github.com/raysantosinsta/MyProjectVRHighlander?utm_source=chatgpt.com)

---

# 📖 REFERÊNCIAS

- [Unity Documentation](https://docs.unity3d.com?utm_source=chatgpt.com)
- [Meta XR Documentation](https://developers.meta.com/horizon/documentation/unity/?utm_source=chatgpt.com)

---

# 👨‍💻 AUTOR

Desenvolvido por **Highlander Oliveira** com foco em aprendizado de Realidade Virtual, XR e experiências imersivas utilizando Unity + Meta XR SDK.
