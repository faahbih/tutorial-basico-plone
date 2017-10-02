Para Centrais de Conteúdos
==========================

	Para itens como Galeria de Imagens, Publicações, Dados Abertos, Infográficos, Videos, Áudios, é necessária a criação do Portlet **Centrais de Conteúdos**, que ficará localizado abaixo do menu principal.

Criar Centrais de Conteúdos
---------------------------

	* Certifique-se que está na **HOME**/**Raíz** do site, clique em **gerenciar portlets**
	* Clique **adicionar portlet** > **texto estático**
	* Nomeie como "Centrais de Conteúdos"
	* Adicione o código HTML abaixo
	* Clique em salvar

Manutenção
----------

	* Vá na **HOME** do site, clique em **gerenciar portlets**
	* Clique em cima de **Centrais de Conteúdos** que está no lado esquerdo;
	* Abrirá uma tela para edição, neste caso há **dois itens** (que estão no formato de lista: **imagens** e **publicações**)

	1. Sempre que for feito a edição de algum dos itens é necessário abrir em forma de **html**, basta clicar no ícone html
	2. Caso queira adicionar um novo item 
		- conforme no manual de gestão do portal padrão há um código para ser usado;
		- url do manual: http://www.secom.gov.br/orientacoes-gerais/comunicacao-digital/gestao-manual-portal-modelo-governo-federal-dez2014.pdf 
		- o código encontra-se na página 298
		- copie o código e remova os itens que não deseja que está entre as tags <ul>..</ul>.

		    + Obs. No site da DGI existe apenas Galeria de Imagens.
		      

Código em HTML da Centrais de Conteúdos
---------------------------------------

.. code-block:: html
    :linenos:

	<ul class="list-central">
		<li class="item-central item-videos first">
			<a class="link-central link-videos internal-link" href="#" target="_self" title="">Vídeos</a>
		</li>
		<li class="item-central item-audios">
			<a class="link-central link-audios internal-link" href="#" target="_self" title="">Áudios</a>
		</li>
		<li class="item-central item-fotos last-item">
			<a class="link-central link-fotos internal-link" href="#" target="_self" title="">Imagens</a>
		</li>
		<li class="item-central item-publicacoes">
			<a class="link-central link-publicacoes internal-link" href="#" target="_self" title="">Publicações</a>
		</li>
		<li class="item-central item-dadosabertos">
			<a class="link-central link-dadosabertos internal-link" href="#" target="_self" title="">Dados Abertos</a>
		</li>
		<li class="item-central item-infograficos">
			<a class="link-central link-infograficos internal-link" href="#" target="_self" title="">Infográficos </a>
		</li>
		<li class="item-central item-aplicativos last-item">
			<a class="link-central link-aplicativos internal-link" href="#" target="_self" title="">Aplicativos </a>
		</li>
	</ul>
