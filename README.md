# aula1b

Personalizacao das cores do cabecalho,
   incluindo a navegacao e a busca */


/* Fundo do cabecalho */
#header {
	border-top: 10px solid #11242e;
	background: #193442;
}

/* Link na navegacao */
#header  #nav a {
	color: #fff;
	background: #193442;
}

/* Link na navegacao: estado hover; */
#header #nav a:hover {
	color: #00C7C0;
}

/* Cor do icone do link na navegacao */
#menu-primary li:before {
	color: #3F5C6B;
}

/* Icone da busca e navegacao
(janela menor que 680px de largura) */
#search-toggle:after,
#search-toggle {
	color: #3F5C6B;
}

/* Icone e texto da busca */
#search-toggle:hover:after,
.search-close .search-text,
#search-toggle:before,
#search-toggle:hover .search-text,
.search-text:hover {
	color: #00C7C0;
}

/* Icone e texto da navegacao */
#nav-toggle span,
#nav-toggle span:before,
#nav-toggle span:after {
	background: #3F5C6B;
}

/* Borda ao lado do icone da busca */
#search-toggle:after,
#search-toggle:before {
	border-left: 1px solid #3F5C6B;

}

/* Borda no link da navegacao e busca (abaixo de 680px) */
#menu-primary > a,
#search-toggle {
	border: 1px solid #3F5C6B;
}

/* Removendo o fundo do item que possui o submenu */
#menu-primary li.menu-item-has-children:hover,
#menu-primary-items .sub-menu li a:hover,
#menu-primary>ul>li.menu-item-has-children:hover>a:hover:after {
	background: none;
}

/* Removendo sombra em volta do sub-menu */
#menu-primary>ul>li.menu-item-has-children:hover>a,
#menu-primary>ul:not(:hover)>li.menu-item-has-children.active>a {
	box-shadow: none;
}

/* Cor de fundo dos itens do submenu */
#header #nav .sub-menu a {
	background: #11242E;
	border-top: 1px solid #193442;
}

/* Removendo a borda da esquerda para larguras acima de 680px */
@media screen and (max-width: 680px) {
	#search-toggle:after {
		border-left: 0;
	}

	#header #menu-primary-items a {
		background: #11242E;
		border-top: 1px solid #193442;
	}

	#menu-primary>ul:before	{
	border-color: transparent transparent #11242E transparent;
	}
}

/* Removendo as bordas para larguras abaixo de 680px */
@media screen and (min-width: 680px) {
	#search-toggle {
		border: none;
	}
}


/* Modo Zen */

/* Fundo do cabecalho */
.zen #header {
	border-top: 10px solid #EDF1F2;
	background: #fff;
}

/* Link na navegacao */
.zen #header  #nav a {
	color: #B3C1C7;
	background: #fff;
}

/* Link na navegacao: estado hover; */
.zen #header #nav a:hover {
	color: #00C7C0;
}

/* Cor do icone do link na navegacao */
.zen #menu-primary li:before {
	color: #B3C1C7;
}

/* Icone da busca e navegacao
(janela menor que 680px de largura) */
.zen #search-toggle:after,
.zen #search-toggle {
	color: #B3C1C7;
}

/* Icone e texto da busca */
.zen #search-toggle:hover:after,
.zen .search-close .search-text,
.zen #search-toggle:before,
.zen #search-toggle:hover .search-text,
.zen .search-text:hover {
	color: #00C7C0;
}

/* Icone e texto da navegacao */
.zen #nav-toggle span,
.zen #nav-toggle span:before,
.zen #nav-toggle span:after {
	background: #B3C1C7;
}

/* Borda ao lado do icone da busca */
.zen #search-toggle:after,
.zen #search-toggle:before {
	border-left: 1px solid #B3C1C7;

}

/* Borda no link da navegacao e busca (abaixo de 680px) */
.zen #menu-primary > a,
.zen #search-toggle {
	border: 1px solid #B3C1C7;
}

/* Removendo o fundo do item que possui o submenu */
.zen #menu-primary li.menu-item-has-children:hover,
.zen #menu-primary-items .sub-menu li a:hover,
.zen #menu-primary>ul>li.menu-item-has-children:hover>a:hover:after {
	background: none;
}

.zen #menu-primary>ul>li.menu-item-has-children:hover>a:hover:after {
	color: #B3C1C7;
}

/* Removendo sombra em volta do sub-menu */
.zen #menu-primary>ul>li.menu-item-has-children:hover>a,
.zen #menu-primary>ul:not(:hover)>li.menu-item-has-children.active>a {
	box-shadow: none;
}

/* Cor de fundo dos itens do submenu */
.zen #header #nav .sub-menu a {
	background: #11242E;
	border-top: 1px solid #193442;
}

/* Removendo a borda da esquerda para larguras acima de 680px */
@media screen and (max-width: 680px) {
	.zen #search-toggle:after {
		border-left: 0;
	}

	.zen #header #menu-primary-items a {
		background: #11242E;
		border-top: 1px solid #193442;
	}

	.zen #menu-primary>ul:before	{
		border-color: transparent transparent #11242E transparent;
	}
}

/* Removendo as bordas para larguras abaixo de 680px */
@media screen and (min-width: 680px) {
	.zen #search-toggle {
		border: none;
	}
}

/* Reduzindo o tamanho dos títulos */
.singular h1.entry-title {
	font-size: 2rem;
}