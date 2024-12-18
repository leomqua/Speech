# Vera_speech

O passo a passo para rodar o código da interface consiste em instalar o Python 3.8.10, ou outra versão compatível, e as bibliotecas necessárias ao projeto. A maioria das bibliotecas pode ser instalada por meio do comando:

pip install -r requirements.txt

Para garantir que todas as bibliotecas estejam instaladas corretamente, utilize os seguintes comandos:

pip install requests json gtts mutagen whisper speechrecognition pillow threading}
pip install opencv-contrib-python>=4.2.0.34 opencv-python==4.1.0.25 torch==1.1.0 torchvision==0.3.0 tqdm==4.45.0 librosa==0.7.0 numpy==1.17.1 numba==0.48

O próximo passo é acessar o repositório do projeto com todas as pastas e diretórios, disponível no seguinte endereço eletrônico:

https://1drv.ms/f/c/0aca311a6ea6733c/EqavQzzrEaRMgZB9ydpv6aMB-QDY9F-QY7OZE6BlEMfd5g?e=sujRKR

Após o download, será necessário ajustar os caminhos dos arquivos no código-fonte. Por exemplo, o caminho para a imagem estática da face do robô deve ser configurado como:

caminho\_face = "C:/face\_hera/codigo/faces/normal1.jpeg"



Além disso, é necessário garantir a existência do diretório "output" dentro da pasta "codigo" do repositório. Esse diretório será utilizado para armazenar temporariamente os arquivos gerados durante a execução do programa, como os vídeos sincronizados com a face do robô. Caso o diretório não exista, ele deve ser criado manualmente ou programaticamente no início do código.
Outro ajuste importante é a alteração da chave de API da OpenAI, utilizada para as respostas e transcrição de áudios na Hera 2.0. A chave pode ser obtida na seção API Keys do site da OpenAI, disponível em:

https://platform.openai.com

Com as dependências instaladas e os diretórios configurados, o projeto pode ser executado. Para isso, abra o terminal, navegue até o diretório principal do projeto e execute o comando:

python main.py

Após concluir esse processo, o programa estará pronto para testes e validação da aplicação.
