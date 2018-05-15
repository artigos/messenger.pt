---
layout: index
title: Messenger
overview: true
---

Messenger é um serviço instantâneo de troca de mensagens lançado pelo Facebook. No entanto, ao contrário da maioria dos aplicativos de mensagens de texto, o Messenger pode fazer muito mais do que apenas enviar textos.

O Facebook Messenger foi lançado em agosto de 2011, após a aquisição de um aplicativo de mensagens em grupo chamado Beluga. Embora seja de propriedade e operado pelo Facebook, o aplicativo e o site são completamente separados do Facebook.com.

Dica: Você não precisa estar no site do Facebook, ou até mesmo ter uma conta no Facebook, para usar o Messenger. Enquanto os dois estão parcialmente conectados, se você tiver uma conta no Facebook, você não precisa ter outra para usar o Messenger.

<span class="latest-article">Últimos artigos sobre o messenger</span>

<ul class="index" markdown="0">
  {% for post in site.posts %}
    <li><a href="{{ post.url }}">{{ post.title }}</a> <span class="date">{{ post.date | date: "%-d/%m/%Y" }}</span></li>
  {% endfor %}
</ul>
