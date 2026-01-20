<div align="right">
  <a href="README.md">
    <img src="https://img.shields.io/badge/Read%20in-English-blue?style=for-the-badge" alt="en">
  </a>
</div>

# LMU Tools - Ferramenta para Le Mans Ultimate

LMU Tools é uma aplicação desktop multifuncional para o simulador de corrida Le Mans Ultimate. Ela foi projetada para ajudar pilotos a otimizar seus setups de carro e estratégias de corrida de forma rápida e intuitiva.

## Funcionalidades

- **Gerador de Setups**: Crie setups de base para qualquer carro e pista do jogo com apenas alguns cliques. Escolha entre diferentes estilos de pilotagem (Qualy, Corrida, Endurance, etc.) para obter uma configuração inicial competitiva.
- **Calculadora de Combustível**: Utilize a telemetria em tempo real do jogo para calcular automaticamente o consumo de combustível por volta, a autonomia do tanque e a estratégia ideal de paradas para a sua corrida.
- **Editor e Comparador de Setups**: Abra e edite arquivos de setup (`.svm`) existentes com uma interface amigável, ou compare dois setups lado a lado para analisar as diferenças.
- **Suporte a Múltiplos Idiomas**: A interface está disponível em Português e Inglês.
- **Temas**: Personalize a aparência da aplicação com temas claro e escuro.

## Instalação

1.  **Baixe o instalador**: Vá para a seção de [Releases](https://github.com/uwaazy/seu-repositorio/releases) e baixe a versão mais recente (`LMU_Tool_Setup.exe`).
2.  **Execute o instalador**: Siga as instruções na tela para instalar a aplicação.
3.  **Primeira Execução**: Na primeira vez que abrir a ferramenta, será solicitado que você aponte para a pasta de instalação do Le Mans Ultimate. Isso é necessário para que a ferramenta possa salvar os setups e instalar o plugin de telemetria.

### Plugin de Telemetria

A ferramenta instalará e ativará automaticamente o plugin `rFactor2SharedMemoryMapPlugin64.dll` na sua pasta do jogo. Este plugin é essencial para a funcionalidade da calculadora de combustível em tempo real.

## Como Usar

### Gerador de Setups

1.  Abra a aplicação e vá para a aba **"Gerador de Setups"**.
2.  Selecione o **Carro** que você irá usar.
3.  Escolha o **Estilo de Setup** (ex: "Corrida", "Qualy").
4.  Selecione uma **Pista Específica** ou marque a opção **"Gerar para todas as pistas"**.
5.  Clique em **"Gerar Setup"**. Os arquivos `.svm` serão criados diretamente na pasta de setups do seu jogo.

### Calculadora de Combustível

1.  Vá para a aba **"Calculadora de Combustível"**.
2.  Entre na pista no Le Mans Ultimate. A ferramenta detectará automaticamente o carro e a pista.
3.  Complete pelo menos uma volta. A ferramenta capturará seu tempo de volta e o consumo de combustível.
4.  Insira a **Duração da Corrida** em minutos.
5.  Clique em **"Calcular Estratégia"** para ver a quantidade de combustível necessária, o número de paradas e a estratégia de stints.

## Contribuindo

Contribuições são bem-vindas! Sinta-se à vontade para abrir uma *issue* para relatar bugs ou sugerir novas funcionalidades.

## Desenvolvido por

- **uWaazy**

<a href="https://ko-fi.com/uwaazy" target="_blank">
  <img src="https://img.shields.io/badge/Support%20my%20Work-FF5E5B?style=for-the-badge&logo=kofi&logoColor=white" alt="Ko-fi Donate">
</a>