Velocímetro

> Milhas, Quilômetros, RPM, Gasolina

> Velocidade MP/H -> Milhas por Hora [x]
> Milhas será a medição secundária do Velocímetro.

> Velocidade KM/H -> Quilômetros por Hora [x]
> Principal marcador de velocidade do veículo, irá ditar a velocidade aproximada do Veículo.

> RPM -> Rotação por Minuto [x]
> Responsável por mostrar a Rotação do Motor.
> Altera o nível de gasolina e a maneira de como ela vai diminuir.

> Gasolina -> [x]
> Medirá o consumo e mostrará o nível de gasolina no tanque de conbustível.
> Trabalha em conjunto com o RPM.

> Algo:
x,y = 100x100
isMovable = true
ChangeColors = only admin or server events
resetData? = only admin

1. Aparecer na tela quando o jogador entrar em veículos catologados.
2. Pressionando uma hotkey será possivel alternar entre MP/H ou KM/H como velocidade principal.
3. Tema do Velocímetro poderá ser alterado por Eventos, Datas Comemorativas e dentre outros. -> Apenas Admin.
4. Mudança de coloração simulando o painel de um veículo, farol desligado = apagado, farol ligado = iluminado.

[1] -> HotKey: * -> [2] -> [3] -> [4]

Acima em \*2:
Terá que ocorrer um animação juntamente com a troca do Medidor de Velocidade "padrão", alternando KM/H e MP/H.

> Stacks: Lua, Eventos, Formato de Desenho.