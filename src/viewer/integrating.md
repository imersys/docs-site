---
title: Integrando na Web
type: viewer
layout: viewer
parent_section: imeplayer
order: 2
---

> Esse guia tem como objetivo auxiliar na integração do **Viewer**  em uma **página** ou **aplicativo Web**. Esse guia é primariamente destinado à **administradores de sistemas** e o conhecimento básico de HTML e CSS é um requisito.


## Iniciando a integração

Para integrar o Viewer em seu html, você deverá incluir o seguinte trecho dentro do `<body>`:

```html
<iframe
      src="https://viewer.imersys.com/lo/a735e894-9256-48b4-b1c4-c3a2550e975c"
      width="500" height="500"
      style="border: 0"
      allow="xr-spatial-tracking,gyroscope,accelerometer,fullscreen">
</iframe>
```


Pronto! Uma característica importante do Viewer é que a integração ocorre sem a necessidade de instalações. Ou seja, uma vez você aplique o trecho de código a cima em seu aplicativo ou página Web a visualização será a seguinte:

<iframe
      src="https://viewer.imersys.com/lo/a735e894-9256-48b4-b1c4-c3a2550e975c"
      width="500" height="500"
      style="border: 0"
      allow="xr-spatial-tracking,gyroscope,accelerometer,fullscreen">
</iframe>

## Configuração

### Chaves de autenticação

Em breve...

### UI

Parâmetros para customização de UI através da URL. Os parâmetros com prefixo `desktop` são para interface Desktop e com prefixo `mobile` para Mobile.

| Parâmetro de URL        | Valor         | Descrição                                                                                   |
| ----------------------- | -----         | ------------------------------------------------------------------------------------------  |
| desktopmenu             | right - left  | Posiciona o menu do lado esquerdo ou direito. Default: left                                 |
| mobileinfobutton        | true - false  | Ativa ou desativa o botão INFO dentro do menu Ambia. Default: true                          |
| mobilehelpbutton        | true - false  | Ativa ou desativa o botão HELP dentro do menu Ambia. Default: true                          |
| mobilearbutton          | true - false  | Ativa ou desativa o botão AR dentro do menu Ambia. Default: true                            |
| mobilefullscreenbutton  | true - false  | Ativa ou desativa o botão FULLSCREEN dentro do menu Ambia. Default: true                    |
| autorotate              | true - false  | Ativa ou desativa a auto rotação do objeto 3D antes da primeira interação. Default: false   | 


#### Exemplo de utilização:

```html

https://viewer.imersys.com/lo/a735e894-9256-48b4-b1c4-c3a2550e975c/#desktopmenu=right

```



## Agora é com você!

Qualquer dúvidas que você tenha na integração, a equipe da Imersys estará super disposta a ajudar. Envie um e-mail para suporte@imersys.com.