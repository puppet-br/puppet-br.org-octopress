---
layout: post
title: "Lançado o Puppet 3.0"
date: 2012-10-01 07a12:14 -0700
comments: true
categories: 
---

Finalmente, depois de 8 release canditates, saiu o Puppet 3.0!

Ele pode ser instalado via os repositórios da PuppetLabs como de constume .

A lista de alterações e melhorias é bem grande, mas podemos destacar:

- Grandes melhorias de performance, principalmente na compilação do catálogo.
- Hiera agora é consultado por padrão para classes parametrizadas.
- Diversas melhorias na instalação de pacotes no Windows.
- O Puppet pode utilizar registros SRV no DNS para localizar o master, servidores de report e arquivos.
- Escopo de variáveis: o escopo dinâmico de variáveis foi removido (Finalmente!)
- Agora pode-se usar `unless` como sinônimo de `if !`
- pluginsync agora é true por padrão (Aleluia!)
- Para mais detalhes sobre a versão 3.0, verificar o anuncio oficial na puppet-users.
