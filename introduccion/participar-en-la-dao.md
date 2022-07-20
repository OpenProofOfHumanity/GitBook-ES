# Participar en la DAO

Una primer aclaración es que al registrarte en PoH y empezar a recibir UBI, tenés acceso a participar de las DAOs de ambos proyectos. Si bien están muy relacionadas, veremos que hay algunos puntos de diferencia. Para simplificar, hablaremos de la DAO de PoH, aclarando algunos puntos de diferencia con la DAO de UBI.

### ¿Cómo es, en la práctica, la DAO?

Podes empezar leyendo y participando tanto en los grupos de telegram como en el [foro](https://gov.proofofhumanity.id/), donde se debate continuamente sobre cuestiones referidas a Proof of Humanity y a UBI. Algunos integrantes plantean inquietudes, otros plantean ideas y demás. Como resultado de ello, se suele armar una propuesta de mejora llamada HIP (Human Improvement Proposal) o UIP (UBI Improvement Proposal). Para que la propuesta sea válida, debe seguir el marco definido en la [HIP-5](https://gov.proofofhumanity.id/t/hip-5-adopt-a-proper-poh-dao-governance-process-to-ensure-hip-quality/393). Sí, hubo una HIP para definir como hacer una HIP :)

En la segunda y tercer fase del proceso de una propuesta se realizan las votaciones. Las mismas se llevan acabo en la plataforma [Snapshot](https://snapshot.org/#/).

#### Snapshot

Es una plataforma ajena a POH. Sin embargo, es la más reconocida y utilizada por la mayoría de DAOS en el ecosistema ethereum dada su transparencia y facilidad para realizar votaciones. Snapshot permite el uso de democracia líquida. Qué significa? Que los participantes votan de manera directa, absteniendose si asi lo quisieran o delegando sus votos a otra wallet.

![](https://i.imgur.com/fnVITHM.png)

Allí debemos conectar la misma billetera que utilizamos para registrarnos en POH para poder emitir nuestro voto. Es importante resaltar que para esto **NO HAY QUE PAGAR NADA**. Solamente se firma un mensaje con nuestra wallet, algo que no tiene costo de gas.

Cuando hay una votación en curso, normalmente se elige entre "Aceptar los cambios" de la propuesta o "No hacer cambios".

![](https://i.imgur.com/qYmbjB2.png)

Una vez seleccionada la opción, nos informará nuestro poder de voto. Hablaremos más de esto un poco más adelante:

![](https://i.imgur.com/NAuyl7F.png)

Utilizando Metamask (es similar para otras wallets) se nos pedirá firmar el mensaje de la votación (repito, sin costo alguno de gas).

![](https://i.imgur.com/3nNXd6n.png)

Una vez que firmemos, nuestro voto ya quedará registrado!

Es importante aclarar que para las HIPs, todo humano registrado en POH tiene el mismo poder de voto. Para las UIPs, el poder de voto es la raíz cuadrada de la cantidad de UBIs que tenés en tu wallet.

Una vez que la votación termina, si la propuesta concluye con votos positivos, la HIP/UIP se implementa. Así de sencillo. Con tu voto, tu punto de vista, tus opiniones y conocimientos aportás a mejorar día a día cada proyecto.

* [Snapshot de PoH DAO](https://snapshot.org/#/poh.eth)
* [Snapshot de UBI DAO](https://snapshot.org/#/ubi-voting.eth)

### Aclaraciones

#### Impactos técnicos de una propuesta

Una propuesta puede tener impactos técnicos, por ejemplo, modificar parámetros de los contratos inteligentes de POH o de UBI (Ejemplo: modificar el costo de depósito inicial). Esto ocurre hoy en día mediante la figura del **Governor**.

El governor es OTRO contrato inteligente que admite el ingreso de "codigo a ejecutarse" en un contrato inteligente (en este caso, el de POH o el de UBI). Son contratos diferentes. Ahora bien, ese "codigo a ejecutarse" requiere que se deje un depósito en garantía ya que se usa la resolución de disputas de Kleros. Si nadie desafía la implementación técnica de la propuesta, el código se ejecuta y se actualiza el contrato inteligente de POH o de UBI. Este mecanismo busca agregar transparencia para cualquier actualización, ya que si el código a ejecutar no hace lo que se acordó en la propuesta, cualquier persona puede apelar y se quedará con el deposito de quién esté intentando actualizar indebidamente el protocolo.

#### Propuestas sin impacto técnico&#x20;

Otras propuestas, en cambio, pueden no tener impacto técnico. En definitiva son acuerdos o convenciones que rigen y guían la gobernanza de la comunidad. La HIP-5 es el ejemplo de ello. Como toda la DAO estuvo de acuerdo de que ese fuera el formato y el proceso para una propuesta, ninguna propuesta en adelante podrá ser válida si no sigue ese marco.

#### Delegaciones de votos

Snapshot permite [delegar el voto](https://snapshot.org/#/delegate). Esta funcionalidad la utilizan en mayor medida las personas que no pueden seguir los debates de la comunidad pero no quieren dejar de aportar su voto. Por lo tanto, delegan su poder de voto en alguien más. Vamos a verlo con un ejemplo:

Juan delega su voto a Alicia. Luego de pagar la transacción con su billetera, en las próximas propuestas que salgan a votación, todo voto que realice Alicia contará con el voto adicional de Juan. Sin embargo, la delegación no implica que Juan no pueda volver a votar. Todo lo contrario, siempre que Juan quisiera votar, lo puede hacer, y en ese caso Alicia volverá a tener solo su voto, sin perjuicio de eliminar la delegación.

_**Recordatorio**_: la opción de delegar el voto CUESTA GAS pero es una única transacción. De allí en adelante, el voto ya queda delegado hasta que se decida eliminar la delegación.
