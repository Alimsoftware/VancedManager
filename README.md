# Vanced Manager
[![Github todos os lançamentos](https://img.shields.io/github/downloads/YTVanced/VancedManager/total.svg?style=for-the-badge)](https://github.com/YTVanced/VancedManager/releases/latest) [![Github todos os lançamentos](https://img.shields.io/github/release/YTVanced/VancedManager.svg?style=for-the-badge)](https://github.com/YTVanced/VancedManager/releases/latest)

# **Agora descontinuado https://twitter.com/YTVanced/status/1503052250268286980**

Olá, quando lançamos o Vanced 15.05.54, as pessoas ficaram chateadas porque ele usava o formato .apks, que era muito mais difícil de instalar do que um arquivo .apk tradicional. Embora tenhamos escrito instruções claras sobre como instalar a nova versão do Vanced, as pessoas ainda não conseguiram descobrir.  
Então pensamos: "por que não criamos um gerenciador para o vanced, que baixe, atualize e desinstale o Vanced e o MicroG, tenha uma interface de usuário fácil e compreensível e tenha menos de 10 MB?" e foi assim que nasceu o Vanced Manager.  
  
Após 3 meses de desenvolvimento, estamos finalmente prontos para apresentar o Vanced Manager às massas. O gerenciador Vanced pode instalar e desinstalar facilmente o Vanced e o Microg, possui várias configurações para personalização e melhor experiência. O Manager vem com uma interface fácil de usar

##### O recurso de download/instalação em segundo plano não é mais suportado devido a problemas com algumas ROMs. NÃO relate problemas relacionados à atividade em segundo plano.

## Contribuições
As solicitações pull devem ser feitas para o branch Dev, pois esse é o branch de trabalho, master é para o código de lançamento.

Para quem deseja fornecer traduções, envie-as para https://crowdin.com/project/vanced-manager, pois também o usamos para o Vanced. Quaisquer problemas com traduções devem ser postados lá também.

## Construção

<div>

[![Build](https://github.com/YTVanced/VancedManager/actions/workflows/debug.yml/badge.svg?branch=dev)](https://github.com/YTVanced/VancedManager/actions/workflows/debug.yml)

</div>

### Usando Android Studio
Clone o repositório, abra-o no Android Studio e crie o aplicativo.

### Usando command line
#### No Windows:
```powershell
.\gradlew.bat assembleDebug
```
#### No Linux/macOS:
```bash
chmod +x gradlew
./gradlew assembleDebug
```
