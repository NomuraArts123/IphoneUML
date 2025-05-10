# IphoneUML

classDiagram
    Iphone --|> ReprodutorMusical
    Iphone --|> AparelhoTelefonico
    Iphone --|> NavegadorInternet

    class ReprodutorMusical{
      -List<String> musicaLista

      -tocar()
      -pausar()
      -selecionarMusica(String musica)
    }
    class AparelhoTelefonico{
      -List<String> contatoLista
      -List<String> recenteContatosLista
      -List<String> chamadaPerdidasLista

      -ligar(String numero)
      -atender()
      -iniciarCorreioVoz()
    }
    class NavegadorInternet{
      
      String urlFavoritas

      -exibirPagina(String url)
      -adicionarNovaAba()
      -atualizarPagina()
    }
