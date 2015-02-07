# Pipocas.Tv-API

Pedido de legendas de uma série
http://api.pipocas.tv/search/serie/[appkey]/[imdb]/[pt|br|all]/[release]

Exemplo de Pedido: http://api.pipocas.tv/search/serie/5f3bebc9d877999c95e86ba233de817a7256b268/1830888/all/The.Exes.S02E11.Hes.Gotta.Have.It.WEB-DL.XviD-TVSR

Resultado:
{

    "Error": "200",
    "Results": 1,
    "Subtitles": 

[

        {
            "Title": "The Exes",
            "Year": "2011",
            "Language": "BR",
            "IMDB": "1830888",
            "DW": "http://api.pipocas.tv/download/5f3bebc9d877999c95e86ba233de817a7256b268/33697/TheExes.zip"
        }
    ]

}

Pedido de legendas de uma série
http://api.pipocas.tv/search/movie/[appkey]/[imdb]/[pt|br|all]/[release]

Exemplo de Pedido: http://api.pipocas.tv/search/movie/5f3bebc9d877999c95e86ba233de817a7256b268/0493464/all/Wanted.2008.DVDRip.XviD-AMIABLE

Resultado:
{

    "Error": "200",
    "Results": 1,
    "Subtitles": 

[

        {
            "Title": "Wanted",
            "Year": "2008",
            "Language": "PT",
            "IMDB": "0493464",
            "DW": "http://api.pipocas.tv/download/5f3bebc9d877999c95e86ba233de817a7256b268/1318/Wanted.zip"
        }
    ]

}

