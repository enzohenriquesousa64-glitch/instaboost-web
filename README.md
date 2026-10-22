# InstaBoost — demonstração web

Projeto visual responsivo para abrir no Chrome de um celular Android.

## Incluído
- Interface gamer preta e roxa.
- Saldo fictício e três missões interativas.
- Dicas de crescimento orgânico.
- Manifest básico para futura experiência PWA.

## Limitações importantes
Esta é apenas uma demonstração visual. Não tem login real, banco de dados, backend, integração com Instagram ou sistema real de moedas. As moedas são temporárias e podem reiniciar ao recarregar. Não insira senhas ou dados reais.

## Para publicar pelo celular
1. Descompacte o ZIP no app Arquivos.
2. Crie uma conta num serviço de hospedagem de site estático, como GitHub Pages ou Firebase Hosting.
3. Crie um repositório/projeto e envie `index.html`, `styles.css`, `app.js`, `manifest.json` e a pasta `assets`.
4. Configure a raiz/pasta publicada conforme as instruções do serviço.
5. Publique e abra o link HTTPS no Chrome.
6. Teste o site antes de compartilhar.

Abrir `index.html` localmente permite conferir a interface, mas um endereço público exige hospedagem. Recursos PWA/instalação no ecrã inicial funcionam melhor em HTTPS.

## O que precisa ser construído para uso real
- Autenticação segura de usuários.
- Banco de dados para salvar saldo e missões.
- Backend para validar recompensas e impedir alterações pelo navegador.
- Regra de proprietário: e-mail verificado conferido no servidor; nunca confiar em um e-mail ou botão definido no JavaScript público.
- Regras de segurança, política de privacidade e termos.
- Qualquer integração com Instagram exigiria configuração própria e cumprimento das regras da plataforma.
