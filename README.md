# OKX trading de futuros: ¿perpetuos o con vencimiento, cuánto capital hace falta y cómo se cobran las comisiones? (guía paso a paso con tabla de contratos)

En OKX puedes operar dos familias de futuros: **perpetuos**, que no vencen y se anclan al precio spot mediante la tasa de financiación, y **futuros con vencimiento**, que se liquidan en una fecha concreta. Con **20–50 USD** se puede abrir y mantener una posición pequeña, y el apalancamiento llega hasta **125x** en pares seleccionados. Debajo tienes qué contrato encaja con cada estilo, cómo se monta la primera orden en la interfaz real y las dos partidas de coste que casi nadie mira antes de operar: el intervalo de la tasa de financiación y la diferencia entre cerrar con límite o con mercado.

> **Resumen rápido:** si solo vas a operar BTC o ETH y piensas mantener la posición abierta, elige perpetuos liquidados en USDT. Si es tu primera vez, prueba la cuenta demo antes de poner dinero real. 👉 [Abrir cuenta en OKX](https://okx.com/join/CASH20)

## Qué contratos puedes operar en OKX

OKX cubre más de **150 activos** en futuros, desde BTC y ETH hasta SOL, ADA, XRP y altcoins de moda. La diferencia práctica entre los tipos de contrato está en si vencen o no y en la moneda con la que se liquidan.

| Tipo de contrato | Se liquida en | ¿Vence? | Apalancamiento | Para quién |
| --- | --- | --- | --- | --- |
| Perpetuo USDT-margined (ej. BTCUSDT Perp) | USDT | No | Hasta 125x en pares seleccionados | Quien quiere mantener la posición sin pensar en fechas |
| Perpetuo crypto-margined | La cripto subyacente (ej. BTC) | No | Igual, según par | Quien prefiere margen y liquidación en la moneda base |
| Futuro con vencimiento (delivery) | USDT o cripto | Sí, en la fecha del contrato | Según contrato | Quien quiere un precio de liquidación fijado de antemano |
| Perpetuos de materias primas | USDT | No | Según contrato | Quien quiere exposición a oro, petróleo o cobre sin poseer el activo |
| X-Perps (renta variable y materias primas) | USD, USDC o USDG | Plazo de hasta 5 años | Según contrato | Perfil avanzado; requiere una evaluación de idoneidad |

Los perpetuos son el producto más líquido de la plataforma y los futuros con vencimiento siguen siendo habituales en BTC y ETH. Un perpetuo se puede mantener abierto de forma indefinida siempre que la cuenta tenga margen suficiente para cubrirlo.

Los perpetuos de materias primas cubren actualmente seis instrumentos: oro (XAUUSDT), plata (AGUSDT), cobre (XCUUSDT), WTI (CLUSDT), Brent (BZUSDT) y gas natural (NGUSDT). Permiten operar el precio sin comprar el metal ni el barril.

Los X-Perps son un producto más reciente: usan margen en UM, se cotizan y liquidan en USD, USDC o USDG, y antes de operarlos hay que pasar una evaluación de idoneidad de unos cinco minutos que se lanza desde la sección de futuros en la app o la web. Si tu cuenta es nueva, empieza por los perpetuos cripto y deja estos para más adelante.

Hay además contratos de eventos, pero solo aparecen en las regiones donde están habilitados. Si no los ves en la app o en la web, no están disponibles para tu cuenta.

## Modo de margen y modo de cuenta: dos capas distintas que conviene no mezclar

Son dos ajustes que se eligen en pantallas diferentes y que la mayoría de tutoriales mezclan en un mismo apartado.

**Modo de margen** (cómo se cubre una posición concreta):

- **Aislado:** el margen se aplica solo a esa posición. Si la liquidan, el resto del saldo de la cuenta no se toca.
- **Cruzado:** todas las posiciones abiertas comparten margen y riesgo, así que una posición en beneficio puede evitar la liquidación de otra.
- **Margen de cartera:** modo avanzado que optimiza los requisitos de margen cuando tienes posiciones que se compensan entre sí.

**Modo de cuenta** (cómo se calcula el margen disponible en el sistema de Cuenta Unificada):

- **Moneda única:** solo el saldo de la moneda que estás operando actúa como margen.
- **Multimoneda:** todos los activos de la cuenta sirven como margen.
- **Cartera:** el modo agregado, pensado para estrategias con coberturas.

El cruce entre ambas capas importa en un caso concreto: en margen cruzado, si tu cuenta es de moneda única se usa como margen todo el saldo de esa moneda; si es multimoneda o de cartera, se usa el valor en dólares de todo el saldo de la cuenta. Es la diferencia entre que un saldo en otra moneda te salve la posición o no cuente para nada.

Si es tu primera operación, usa **aislado**. El riesgo queda limitado a una posición y sabes exactamente cuánto puedes perder antes de abrirla.

## Cómo se opera, paso a paso

1. **Crea la cuenta y completa el KYC.** Sin verificación el acceso queda limitado.
2. **Ingresa fondos** por cripto o por fiat desde el panel principal.
3. **Activa los futuros:** en el menú Trade, selecciona Futures. La plataforma te guía por el proceso de activación.
4. **Transfiere saldo a la cartera de futuros.** Es la cartera que se usa como margen; el saldo de la cartera de fondos no sirve para abrir posiciones.
5. **Elige el contrato.** Primero el tipo de margen (USDT o cripto), luego el par. Para el ejemplo: BTCUSDT Perp, donde USDT es la moneda de liquidación y BTC la unidad de precio.
6. **Fija modo de margen y apalancamiento.** Baja el apalancamiento hasta que entiendas cómo se mueve tu margen con el precio.
7. **Configura la orden.** Puedes usar orden a mercado, límite o condicional. Si necesitas ejecución inmediata, existe la opción BBO (mejor precio de compra y venta disponible). Antes de pulsar Buy (Long) o Sell (Short) puedes añadir take profit y stop loss con sus condiciones.
8. **Gestiona y cierra.** En la ventana de posiciones puedes cerrar introduciendo precio y cantidad y pulsando Close, o usar MKT Close All para salir de toda la posición a mercado.

La web y la app tienen las mismas funciones: operativa de futuros, ajuste de margen y alertas. La app muestra la tasa de financiación en la parte superior del panel de órdenes y la web en la cabecera del dashboard.

## Comisiones: el 0.02% es solo el punto de partida

OKX no tiene planes ni suscripción mensual. Cobra una comisión por operación, que en futuros arranca en **0.02%** según la comparativa publicada por la propia plataforma, y una tasa de financiación en los perpetuos. La tarifa exacta depende de tu nivel, del par y de la región, así que confírmala en la tabla de comisiones oficial antes de calcular nada. Y se paga dos veces: al abrir y al cerrar.

**El coste que se acumula sin que lo veas es la tasa de financiación.** En un perpetuo, largos y cortos se pagan entre sí a intervalos regulares para que el precio del contrato se mantenga pegado al spot. El intervalo no es igual en todos los contratos: BTCUSDT Perpetual liquida cada **8 horas**, mientras que COMPUSDT Perpetual liquida cada **4 horas**. El intervalo aparece entre paréntesis junto a la etiqueta de la tasa. En la práctica, un contrato de 4 horas genera seis pagos al día y uno de 8 horas, tres.

Para verlo, pulsa el campo **Funding rate / Countdown** en la cabecera del dashboard (web) o en la parte superior del panel de órdenes (app). El panel de detalle muestra cinco datos:

- la tasa actual y su equivalente anualizado
- la dirección: qué lado paga en la próxima liquidación
- el tope y el suelo de la tasa para ese contrato
- la cuenta atrás hasta el siguiente pago

El menú **Information** del panel de futuros añade la guía de niveles de posición, el historial de liquidaciones y las tasas de financiación del contrato.

**El segundo coste es cómo cierras.** MKT Close All sale al precio de mercado y paga la comisión de taker, la más alta. Está pensado para salir ya, en movimientos extremos. Cerrar con orden límite es más barato en comisiones y no tiene sentido pagar de más cuando el mercado está tranquilo.

Si quieres ver las tarifas aplicadas a tu cuenta antes de operar: 👉 [Consultar el acceso de registro de OKX](https://okx.com/join/CASH20)

## Apalancamiento y liquidación: el caso de 1.000 USD a 20x

Abrir un contrato perpetuo de BTC por 1.000 USD con apalancamiento 20x requiere **50 USD de margen**. El apalancamiento multiplica la exposición, y con ella las ganancias y las pérdidas: un movimiento del 5% en contra sobre esa posición se come el margen completo.

La liquidación se dispara cuando el saldo de margen cae por debajo del **nivel de mantenimiento** que OKX fija para cada contrato y tamaño de apalancamiento. La plataforma avisa en tiempo real cuando te acercas a un margin call y su sistema de control de riesgo ejecuta el cierre forzoso para evitar saldos negativos. Dos hábitos que evitan sustos: mirar el nivel de margen después de cada operación y dejar puesta una orden de stop loss desde el principio.

El requisito mínimo de margen empieza en unos pocos USDT, pero operar con eso no tiene recorrido. La referencia práctica para abrir y mantener una posición pequeña son **20–50 USD**, y siempre con dinero que puedas permitirte perder.

## Cómo se compara con otras plataformas

La siguiente tabla reproduce la comparativa publicada por OKX. Son datos de overview, no una tabla de tarifas por niveles, y la propia plataforma advierte que activos, apalancamiento y seguros varían según región y fecha.

| Plataforma | Activos | Apalancamiento máx. | Comisión desde | Prueba de reservas |
| --- | --- | --- | --- | --- |
| OKX | 150+ | Hasta 125x | 0.02% | Sí |
| Binance | 100+ | Hasta 125x | 0.02% | Parcial |
| Bybit | 60+ | Hasta 100x | 0.01% | Parcial |
| Robinhood | Limitado (solo EE. UU.) | Sin dato | 0% (spot) | No |
| CME | BTC, ETH | ~3–10x (variable) | Variable | Sí (regulado) |

Bybit figura con una comisión de partida más baja que la de OKX en esa columna, 0.01% frente a 0.02%. En cobertura de activos y apalancamiento máximo, OKX y Binance empatan en la parte alta de la tabla; CME queda para quien necesite un entorno regulado y solo quiera BTC o ETH, con mucho menos apalancamiento.

## Protección de fondos y cuenta de práctica

OKX mantiene un fondo de seguros que cubre los déficits que el colateral no alcanza a pagar cuando una caída fuerte provoca liquidaciones masivas. En la práctica reduce la probabilidad de que te toque una reducción automática de posiciones o una pérdida no explicada por tu operación.

Las reservas se publican con auditoría de terceros y respaldo 1:1 de los fondos de los usuarios; los informes de BTC, ETH y otros activos están disponibles en la web. A eso se suman almacenamiento en frío, autenticación multifactor y soporte por chat y correo 24/7 en varios idiomas.

Antes de arriesgar dinero, la cuenta demo: se activa desde el dashboard, entrega créditos virtuales y replica las funciones de la plataforma real, incluidas las órdenes, el margen y el cierre de posiciones. Es la forma más barata de comprobar cómo se comporta tu margen en un par concreto.

👉 [Abrir una cuenta en OKX y activar el modo demo](https://okx.com/join/CASH20)

## Preguntas frecuentes

**¿Cuánto dinero hace falta para operar futuros en OKX?**
El margen mínimo arranca en unos pocos USDT, pero para abrir y mantener una posición pequeña con cierta holgura se suele partir de 20–50 USD. Con menos, cualquier movimiento normal del precio te saca.

**¿Me pueden liquidar la cuenta entera?**
Con margen aislado, la liquidación afecta solo a esa posición y el resto del saldo queda intacto. Con margen cruzado, todas las posiciones comparten el margen de la cuenta, así que una liquidación puede arrastrar más.

**¿Perpetuo o futuro con vencimiento?**
El perpetuo no vence, se mantiene abierto mientras haya margen y paga tasa de financiación de forma periódica. El futuro con vencimiento tiene fecha de liquidación y no depende de esa tasa, pero te obliga a planificar la salida.

**¿Puedo practicar sin dinero real?**
Sí. La cuenta demo entrega créditos virtuales y funciona igual que la plataforma real, con las mismas órdenes y controles de margen.

**¿Qué criptomonedas tienen futuros?**
Más de 150 activos, incluidos BTC, ETH, SOL, ADA y XRP, además de altcoins que se van añadiendo. La lista cambia y varía por región.

**¿Cada cuánto se cobra la tasa de financiación?**
Depende del contrato. BTCUSDT Perpetual liquida cada 8 horas y COMPUSDT Perpetual cada 4 horas; el intervalo aparece entre paréntesis junto a la etiqueta de la tasa en el panel.

## Cómo elegir según tu caso

Si solo vas a operar BTC o ETH y quieres mantener la posición abierta sin fechas, elige perpetuos liquidados en USDT. Si necesitas un precio de salida fijado de antemano, ve a los futuros con vencimiento. Para oro, petróleo o cobre, los perpetuos de materias primas dan exposición al precio sin poseer el activo. Si vienes del mercado spot y no piensas usar apalancamiento, los futuros no te aportan nada: sigue en spot.

Antes de confirmar cualquier orden, revisa dos cosas en el panel. Primero, la tasa de financiación actual, su dirección y el intervalo de liquidación de ese contrato concreto: determina lo que te cuesta mantener la posición cada día. Segundo, el nivel de mantenimiento que corresponde a tu tamaño de posición y apalancamiento en la guía de niveles; es el número que decide a partir de qué precio te liquidan.

👉 [Empezar en OKX desde el formulario de registro](https://okx.com/join/CASH20)
