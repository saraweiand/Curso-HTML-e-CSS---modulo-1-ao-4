Todas as tabelas de HTML tem a seguinte hierarquia (simples):<br>
TABLE = tabela<br>
    TABLE ROW (tr) = linha de tabela<br>
        TABLE HEADER (th) = cabeçalho de tabela<br>
        TABLE DATA (td) = dado de tabela<br>

Todas as tabelas de HTML tem a seguinte hierarquia (grande):<br>
    TABLE<br>
        CAPTION (legenda)<br>
        THEAD (cabeça)<br>
            TR, TD, TH<br>
        TBODY (corpo)<br>
            TR, TD, TH<br>
        TFOOT (footer)<br>
            TR, TD, TH<br>
<br>
<br>
ODD: vai fazer as células ímpares ficarem cinza (2n-1)<br>
EVEN: vai fazer as células pares ficarem cinzan(2n)<br>
<br>
<br>
tbody > tr:nth-child(2n)<br>
De duas em duas ele vai colocando uma target cinza<br>
overflow-x: auto; Conteúdo que transborda
