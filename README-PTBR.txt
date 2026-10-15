MASSA DELIVERY — PROJETO ANDROID STUDIO

Este é o projeto-fonte para compilar um APK de teste. Ainda não é um APK pronto.
Inclui o cardápio web dentro de um aplicativo Android (WebView), logo, carrinho, taxa de entrega R$ 3,00 e encaminhamento do pedido ao WhatsApp.

COMO GERAR O APK NO COMPUTADOR
1. Instale o Android Studio pelo site oficial: https://developer.android.com/studio
2. Extraia o ZIP para uma pasta no computador.
3. Abra o Android Studio e escolha Open.
4. Selecione a pasta MassaDeliveryAndroidStudio (a pasta que contém settings.gradle).
5. Aguarde o Gradle sincronizar. Se pedir para instalar Android SDK 35 ou Build Tools, aceite.
6. No menu, selecione Build > Build Bundle(s) / APK(s) > Build APK(s).
7. Quando terminar, clique em locate. O APK de teste normalmente fica em app/build/outputs/apk/debug/app-debug.apk.
8. Transfira app-debug.apk para o celular e abra o arquivo para instalar. Talvez seja necessário permitir instalação dessa fonte nas configurações do Android.

REQUISITOS
- Android Studio atual
- JDK 17 (o Android Studio costuma gerenciar isso automaticamente)
- Conexão à internet na primeira sincronização do Gradle

ATENÇÃO
- A primeira compilação deve ser feita em um computador, não apenas no celular.
- O WhatsApp abre para o cliente enviar o pedido; Pix/cartão não são processados dentro do app.
- Antes da Play Store, será necessário gerar um Android App Bundle (AAB), configurar assinatura, política de privacidade e testar o app conforme as regras atuais do Google Play.
