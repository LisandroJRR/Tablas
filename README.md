<!--Lisandro Josafath Rocha Ramos-->
<!DOCTYPE html>
<html lang="es">
<style>
    table{
        width: 20%;
        border-collapse: collapse;
    }
    th, td {
        border: 1px solid black;
        padding: 8px;
        text-align: left;
    }
    th{
        background-color: #f2f2f2;
    }
    caption{
        front-size: 1.5em;
        margin: 10px;
    }
</style>
<head>
    <meta charset="UTF-8">
    <title>Tablas - HTML</title>
</head>
<body>
    <h1>Tablas en HTML</h1>
    <hr>
    <h4>Tabla 1</h4>
    <table>
        <tr>
            <th>Mes</th>
            <th>Visitas</th>
            <th>Clicks</th>
        </tr>
        <tr>
            <td>Enero</td>
            <td>500</td>
            <td>25</td>
        </tr>
        <tr>
            <td>Febrero</td>
            <td>600</td>
            <td>20</td>
        </tr>
        <tr>
            <td>Marzo</td>
            <td>1000</td>
            <td>50</td>
        </tr>
    </table>
    <hr>
    <h4>Tabla 2</h4>
    <table>
        <tr>
            <th>Mes</th>
            <th>Visitas</th>
            <th>Clicks</th>
        </tr>
        <tr>
            <td>Enero</td>
            <td>500</td>
            <td>25</td>
        </tr>
        <tr>
            <td>Febrero</td>
            <td>600</td>
            <td>20</td>
        </tr>
        <tr>
            <td>Marzo</td>
            <td>1000</td>
            <td>50</td>
        </tr>
    </table>
    <hr>
    <h4>Tabla 3</h4>
    <table>
        <tr>
            <th>Paises</th>
            <th>Medallas</th>
        </tr>
        <tr>
            <td>USA</td>
            <td>133</td>
        </tr>
        <tr>
            <td>China</td>
            <td>25</td>
        </tr>
        <tr>
            <td>España</td>
            <td>3</td>
        </tr>
        <tr>
            <td>Francia</td>
            <td>6</td>
        </tr>
    </table>
    <hr>
    <h4>Tabla 4</h4>
    <table>
        <tbody>
            <tr>
                <td colspan="2">A</td>
                <td>B</td>
                <td>C</td>
            </tr>
            <tr>
                <td rowspan="3">D</td>
                <td colspan="2">E</td>
                <td>F</td>
            </tr>
            <tr>
                <td>G</td>
                <td colspan="2"> H</td>
            </tr>
            <tr>
                <td>I</td>
                <td>J</td>
                <td>K</td>
            </tr>
        </tbody>
    </table>
    <hr>
    <h4>Tabla 5</h4>
    <table>
        <tbody>
            <tr>
                <td>mes</td>
                <td>enero</td>
                <td>febrero</td>
                <td>marzo</td>
                <td>abril</td>
                <td>mayo</td>
                <td>junio</td>
            </tr>
            <tr>
                <td>Pib</td>
                <td>0.2</td>
                <td>0.4</td>
                <td>0.2</td>
                <td>0.3</td>
                <td>0.1</td>
                <td>0.2</td>
            </tr>
            <tr>
                <td>pnb</td>
                <td>1.3</td>
                <td>1.2</td>
                <td>1.1</td>
                <td>1.9</td>
                <td>1.7</td>
                <td>1.6</td>
            </tr>
        </tbody>
    </table>
    <hr>
    <h4>Tabla 6</h4>
    <table>
        <tbody>
        <tr>
            <td colspan="2" >item 1</td>
            <td rowspan="2">Item 2</td>
            <td colspan="2">Item 3</td>
        </tr>
        <tr>
            <td colspan="2">Item 4</td>
            <td colspan="2">Item 5</td>
        </tr>
        </tbody>
    </table>    <hr>
    <h4>Tabla 7</h4>
    <table>
        <tbody>
        <tr>
            <td rowspan="2">Item 1</td>
            <td>Item 2</td>
            <td>Item 3</td>
            <td>Item 4</td>
        </tr>
        <tr>
            <td>Item 5</td>
            <td>Item 6</td>
            <td>Item 7</td>
        </tr>
        </tbody>
    </table>
    <hr>
    <h4>Tabla 8</h4>
    <table>
        <tbody>
        <tr>
            <td>Item 1</td>
            <td colspan="2">Item 2</td>
        </tr>
        <tr>
            <td>Item 3</td>
            <td>Item 4</td>
            <td>Item 5</td>
        </tr>
        </tbody>
    </table>
    <hr>
    <h4>Tabla 9</h4>
    <table>
        <tbody>
            <tr>
                <th colspan="2">Head1</th>
                <th colspan="2">Head2</th>
            </tr>
            <tr>
                <th>Head 3</th>
                <th>Head 4</th>
                <th>Head 5</th>
                <th>Head 6</th>
            </tr>
            <tr>
                <td>A</td>
                <td>B</td>
                <td>C</td>
                <td>D</td>
            </tr>
            <tr>
                <td>E</td>
                <td>F</td>
                <td>G</td>
                <td>H</td>
            </tr>
        </tbody>
    </table>
    <hr>
    <h4>Tabla 10</h4>
    <table>
        <tbody>
        <tr>
            <th>Head1</th>
            <td>Item 1</td>
            <td>Item 2</td>
            <td>Item 3</td>
        </tr>
        <tr>
            <th>Head2</th>
            <td>Item 4</td>
            <td>Item 5</td>
            <td>Item 6</td>
        </tr>
        <tr>
            <th>Head3</th>
            <td>Item 7</td>
            <td>Item 8</td>
            <td>Item 9</td>
        </tr>
        </tbody>
    </table>
</body>
</html>
