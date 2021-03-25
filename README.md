
# Curso de SEO Wordpress: Otimize o ranqueamento do seu site. Alura - 22/03/2021 - 4h
  

 1. Fazer as configurações inicias: entrar no Dashboard > Settings > ajustar as configurações de: Site Language.
 2. Renomear as categoria padrão: Posts > Categorias > Editar. (Slug é a url);
 3. Visibilidade nos mecanismos de busca: marcar o check-box, só desativar se o site já estiver pronto - com essa opção marcada quer dizer que o site ainda não estar pronto para ser indexado (O que acontece por trás dos panos é que o wordpress coloca por padrão a tag _noindex_ nas páginas do seu site, dando assim uma dica para os buscadores de que essas páginas não devem ser indexadas. Ao desabilitar a opção, ele simplesmente remove essa tag.);
 4. Links permanentes: é a URL, deve conter palavras chave nele, ser o mais limpo possível para ser indexado. Selecionar o link permanente: Nome do Post (o indexador vai entender qual é a palavra-chave do seu titulo);

## SEO para imagens

 - Renomear as imagens pois o nome do arquivo é importante para a indexação no Google (usar i hífen como separador de palavras);
 - Ao inserir a imagem deve colocar o titulo, a legenda, texto alternativo e a descrição tudo igual, pois dependendo da template ele vai usar campos diferentes para a indexação.
 - Sempre usar imagens no posts e se for um infográfico é melhor ainda.

## Instalação o Yoast no Wordpress e a otimização completa

Plugins > no campo de pesquisa colocar o nome Yoast SEO > Instalar agora > Ativar. Pesquisar o post que foi criado dentro do wordpress, no final da página vai ter informações sobre o Yoast SEO. 

Ir em 'Focus keyword' e digitar a palavra-chave que pretende ranquear. Ranquear palavras chaves diferentes para cada post.

**Dicas:** 
 - deve conter links que direcionam para outros sites que tem haver com o assunto do post;
 - O ideal é que no começo da url apareça a palavra-chave (a url não precisa ser igual ao titulo do post);
 - Ranquear palavras chaves diferentes para cada post;
 - Os subtítulos tem um peso benéfico para o ranqueamento dos buscadores, dessa forma é interessante colocar a palavra chave no subtítulo também;
 - AS fotos devem conter as palavras chaves (Alt atribute);
 - O primeiro parágrafo deve conter a palavra chave ou pelo menos no começo do post.
 - O titulo deve conter a palavra-chave no inicio.
 - Meta description: é só clicar no preview e editar e deve conter a palavra chave;

**Evitar publicação duplicada:** 
Detalhes escondidos: categoria, data, home, página do autor, tags (se a publicação não estiver categorizada ele pode aparecer nesses 5 links, ou seja, a indexação vai duplicar o conteúdo, podendo ser penalizado).
Ir em Menu > SEO > aba Recursos > habilitar as configurações avançadas > Salvas as alterações.
Vai abrir novos submenus abaixo do SEO, clicar em Títulos & Metadados > aba Taxonomias (são links alternativos, que vai indexar os links) > escolher as opções que devem ser indexadas. Ir na aba Arquivo > e fazer o mesmo procedimento.

**Páginações:** evitar indexar as paginações dos conteúdo. Ir em Menu > SEO > Títulos e Metadados > aba Outros desabilitar a indexação de páginas e arquivos.

## Habilite o Search Console

Monitorar como o site está de acordo com as buscas. (O Search Console é uma ferramenta básica para quem quer trabalhar com SEO e traz vários recursos e informações interessantes que você pode se basear até mesmo para decidir quais novos conteúdos ele deve ter).

Acessar o [Google Search Console](https://search.google.com/search-console/welcome?hl=pt-BR): adicionar o site, e a sugestão para autenticar o site é adicionar a opção HTML tag. Copiar o código > vai no Wordpress > Menu > Aparência > Editar > seleciona a opção 'Cabeçalho do tema' no inicio da tag <head..> colar o código > Salvar.
 
**Sitemap:** é uma lista de endereços/páginas que o site possui. O Yoast faz automaticamente o sitemap. Wordpress > Menu > SEO > Sitemaps XML > a opção deve estar habilitada > clicar em XML Sitemap > copiar o endereço do Sitemap > ir no Search Console > clicar em sitemaps > e colar o endereço copiado > e selecionar para fazer a indexação (Fetch as Google - Essa é a opção que faz que o site entre na fila de indexação. A opção Fetch as Google permite solicitar que uma nova indexação seja feita. Fique apenas atento pois há um limite de vezes que essa solicitação pode ser feita dentro de um determinado período de tempo. Sempre consulte quantos "créditos" você possui antes de fazer essa submissão). Depois de uns dias o site começa a aparecer no Google.

**Site seguro:** o Google dá prioridade aos site seguros que possuem HTTS/SSL
Para cada provedor de servidor tem um tipo de configuração (1and1.com é gratuito). Configurar o certificado SSL.

Uma boa dica caso você esteja criando um site e sem possuir um provedor de preferência é verificar se seu provedor fornece uma chave SSL para habilitação de HTTPS em seu site. Atualmente, muitos provedores fornecem essas chaves gratuitamente, com processo de instalação muito simples.

*Fim!*
