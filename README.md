# afilio
Desafio Afilio


| Domain | Method   | URI            | Name | Action                                          | Middleware   |
+--------+----------+----------------+------+-------------------------------------------------+--------------+
|        | POST     | campanhas      |      | App\Http\Controllers\CampanhaController@store   | web          |
|        | GET|HEAD | campanhas      |      | App\Http\Controllers\CampanhaController@index   | web          |
|        | PUT      | campanhas/{id} |      | App\Http\Controllers\CampanhaController@update  | web          |
|        | GET|HEAD | campanhas/{id} |      | App\Http\Controllers\CampanhaController@show    | web          |
|        | DELETE   | campanhas/{id} |      | App\Http\Controllers\CampanhaController@destroy | web          |
|        | GET|HEAD | criativos      |      | App\Http\Controllers\CriativoController@index   | web          |
|        | POST     | criativos      |      | App\Http\Controllers\CriativoController@store   | web          |
|        | GET|HEAD | criativos/{id} |      | App\Http\Controllers\CriativoController@show    | web          |
|        | PUT      | criativos/{id} |      | App\Http\Controllers\CriativoController@update  | web          |
|        | DELETE   | criativos/{id} |      | App\Http\Controllers\CriativoController@destroy | web          |
|        | POST     | gerentes       |      | App\Http\Controllers\GerenteController@store    | web          |
|        | GET|HEAD | gerentes       |      | App\Http\Controllers\GerenteController@index    | web          |
|        | PUT      | gerentes/{id}  |      | App\Http\Controllers\GerenteController@update   | web          |
|        | DELETE   | gerentes/{id}  |      | App\Http\Controllers\GerenteController@destroy  | web          |
|        | GET|HEAD | gerentes/{id}  |      | App\Http\Controllers\GerenteController@show     | web          |
+--------+----------+----------------+------+-------------------------------------------------+--------------+


