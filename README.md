# projetoapp


/*

## Ativar a depuração do Celular no modo desenvolvedor clicando 4x na versão do sistema em Sobre o Telefone. ##

para identificar o dispositivo que está conectado pelo cabo USB
adb devices

é recomendado utilizar o driver USB do Google https://developer.android.com/studio/run/win-usb
forçar a conexão do dispositivo pelo usb
adb usb

Reiniciar o servidor ADB
adb kill-server
adb start-server
adb devices


instalador do firebase para o banco de dados para validação online no terminal do pc como ADM
npm install -g firebase-tools


=================
FIREBASE ONLINE
=================

Primeiro deve ser feito o cadastro no firebase e depois cadastrar o seu projeto na plataforma.

Em seguida irá realizar o procedimento abaixo para adicionar o seu projeto

========================================================================================================================================
Adicionar o Firebase ao seu app do Flutter

Preparar seu espaço de trabalho
Usar a CLI do FlutterFire é o jeito mais fácil de começar.

Antes de continuar, certifique-se de:

Instalar a CLI do Firebase e fazer login (execute firebase login)
Instalar o SDK do Flutter
Criar um projeto do Flutter (execute flutter create)

========================================================================================================================================

Instalar e executar a CLI do FlutterFire
Em qualquer diretório, execute o comando:

dart pub global activate flutterfire_cli
Em seguida, na raiz do diretório do seu projeto do Flutter, execute o comando:

flutterfire configure --project=projetoapp-716d8
Com isso, seus apps são registrados automaticamente por plataforma com o Firebase,
e um arquivo de configuração lib/firebase_options.dart é adicionado ao seu projeto do Flutter.

========================================================================================================================================

Inicializar o Firebase e adicionar plug-ins
Para inicializar o Firebase, chame Firebase.InitializeApp no pacote firebase_core com a configuração do seu novo arquivofirebase_options.dart:

import 'package:firebase_core/firebase_core.dart';
import 'firebase_options.dart';

// ...

await Firebase.initializeApp(
options: DefaultFirebaseOptions.currentPlatform,
);
Depois adicione e comece a usar os plug-ins do Flutter para os produtos do Firebase que quiser.

Observação: se usar o Analytics ou o Monitoramento de desempenho, talvez você tenha que seguir algumas etapas adicionais de configuração.

========================================================================================================================================

ATUALIZAR AS DEPENDENCIAS QUE SERÃO UTILIZADAS NO APLICATIVO NO ARQUIVO PUBSPEC.YAML

# DEPENDENCIAS PADRÃO
#dependencies:
#flutter:
# sdk: flutter
#==============================================

# INSTALAÇÃO DE DEPENDENCIAS COM O FIREBASE
#dependencies:
#flutter:
#sdk: flutter
#firebase_core: latest_version (informar a versão do firebase que será utilizada)
#firebase_auth: latest_version (informar a versão do firebase que será utilizada)

*/
