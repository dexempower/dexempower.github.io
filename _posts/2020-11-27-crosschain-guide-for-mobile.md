---
layout: page
title: "Crosschain Guide for Mobile"
date: 2020-11-27 05:20:00 +0800
categories: guides yield-farming
---

<p align="center">
<img src="/assets/SymbloxLogoName.png" height="64"/>
</p>

# Guía Cross-Chain para Móviles

##### Instalando Velas Defi Wallet  
Descarga Velas DeFi Wallet en https://symblox.io.  

# Configurando Velas Defi Wallet

<details>
<summary>Agregar la red de Ethereum.</summary>  
<br>
  
Haga clic en la pestaña 'Ajustes', luego elija "Seleccionar redes activas"  
<p align="center">
<img src="../assets/Bridge_1.png" width="400"/>
</p>  

Elija 'Ethereum' y luego haga clic en 'Guardar'.
<p align="center">
<img src="/assets/Bridge_2.png" width="400"/>
</p>  
</details>

<details>
<summary>Añadiendo el contrato del token USDT para Ethereum y Velas.</summary>  
<br>
  
Haga clic en la pestaña 'Monedero', luego haga clic en 'Añadir / Ocultar tokens'.

<p align="center">
<img src="/assets/Bridge_3.png" width="400"/>
</p>  

Haga clic en el signo '+'.  
<p align="center">
<img src="/assets/Bridge_4.png" width="400"/>
</p>  

Pegue la siguiente dirección en el campo 'Dirección del contrato' para agregar el token USDT en Ethereum. Los otros campos se completarán automáticamente cuando pegue la dirección.
USDT en Ethereum:**0xdAC17F958D2ee523a2206206994597C13D831ec7**  
<p align="center">
<img src="/assets/Bridge_5.png" width="400"/>
</p>  

Repita el proceso para agregar USDT en Velas.
USDT en Velas: **0x4b773e1ae1baa4894e51cc1d1faf485c91b1012f**  
<p align="center">
<img src="/assets/Bridge_6.png" width="400"/>
</p>  

Si aún no ha agregado el token SYX, puede repetir el proceso anterior para agregar SYX. 
Dirección del token SYX: **0x2de7063fe77aAFB5b401d65E5A108649Ec577170**  
<p align="center">
<img src="/assets/AddToken_3.png" width="400"/>
</p>    
</details>

<details>
<summary>Añadiendo contrato de token WETH para Ethereum y Velas.</summary>  
<br>
  
Haga clic en la pestaña 'Monedero', luego haga clic en 'Añadir / Ocultar tokens'.

<p align="center">
<img src="/assets/Bridge_3.png" width="400"/>
</p>  

Haga clic en el signo '+'.  
<p align="center">
<img src="/assets/Bridge_4.png" width="400"/>
</p>  

Pegue la siguiente dirección en el campo 'Dirección del contrato' para agregar el token WETH en Ethereum. Los otros campos se completarán automáticamente cuando pegue la dirección.
WETH en Ethereum: **0xc02aaa39b223fe8d0a0e5c4f27ead9083c756cc2**  
<p align="center">
<img src="/assets/WETH_CONTRACT.png" width="400"/>
</p>  

Repita el proceso para agregar WETH en Velas: 
**V67RMNXTgYKi9CsmrSXvFfLAiubfWB5p34**  
<p align="center">
<img src="/assets/VWETH_CONTRACT.png" width="400"/>
</p>  
</p>    
</details>
 
# Utilizando TokenBridge  

<details>
<summary>Transfiriendo USDT en Ethereum a Velas blockchain.</summary>  
<br>
  
Haga clic en la pestaña 'Symblox', luego vaya a la página de inicio: <a href="https://symblox.io/" target="_blank">https://symblox.io/</a>  
Haga clic en el botón 'Abrir Cross-Chain' o escriba en el campo de dirección:  
<a href="https://x.symblox.io/" target="_blank">https://x.symblox.io/</a>  
<p align="center">
<img src="/assets/Bridge_7.png" width="400"/>
</p>  

(1) Haga clic en el botón de menú.
(2) Si aún no ha elegido 'Ethereum' , haga clic en 'Conectado a:' para elegir la red Ethereum.
<p align="center">
<img src="/assets/Bridge_8.png" width="400"/>
</p>  

Elija 'Ethereum'.
<p align="center">
<img src="/assets/Bridge_19.png" width="400"/>
</p>  

Haga clic en 'Conectar Monedero'.
<p align="center">
<img src="/assets/Bridge_20.png" width="400"/>
</p>  

>The first time you use the cross-chain, the smart contract will require permission before accessing your wallet. Therefore it requires you to *unlock* before transferring.   

Ingrese la cantidad a transferir y luego haga clic en 'Unlock/Desbloquear'.
<p align="center">
<img src="/assets/Bridge_9.png" width="400"/>
</p>  

Haga clic en 'Confirmar' para enviar o haga clic en 'Editar' para cambiar manualmente las tarifas de gas.  
<p align="center">
<img src="/assets/Bridge_10.png" width="400"/>
</p>  

> Debido a la gran congestión en la red Ethereum, las transacciones pueden llevar mucho tiempo o incluso atascarse. Si ha esperado un período de tiempo suficiente y todavía está en la pantalla 'Cargando ...', intente volver a cargar la página web para ver si su transacción se ha liquidado.

<p align="center">
<img src="/assets/Bridge_11.png" width="400"/>
</p>  

Una vez que haya 'Desbloqueado', haga clic en 'Transferir'.
<p align="center">
<img src="/assets/Bridge_12.png" width="400"/>
</p>  

Verifique el monto de su transferencia y luego haga clic en 'Continuar'.
<p align="center">
<img src="/assets/Bridge_13.png" width="400"/>
</p>  

Después de la transferencia, puede verificar su 'Balance' para ver la cantidad transferida. 
<p align="center">
<img src="/assets/Bridge_14.png" width="400"/>
</p>  
</details>

<details>
<summary>Transfiriendo USDT de Velas de vuelta a la cadena de bloques Ethereum.</summary>
<br>

(1) Haga clic en el botón de menú.
(2) Si aún no está conectado a Velas, haga clic en 'Conectado a:' para cambiar su red actual.  
<p align="center">
<img src="/assets/Bridge_15.png" width="400"/>
</p>  

Elija 'Velas'.
<p align="center">
<img src="/assets/Bridge_16.png" width="400"/>
</p>  

Ingrese la cantidad a enviar y luego haga clic en 'Transfer/Transferir'.
<p align="center">
<img src="/assets/Bridge_17.png" width="400"/>
</p>  

Verifique la cantidad y luego haga clic en 'Continuar'.
<p align="center">
<img src="/assets/Bridge_18.png" width="400"/>
</p>  
</p>  
</details>

<details>
<summary>Transferring WETH on Ethereum to Velas blockchain.</summary>  
<br>

Dentro de la aplicación DeFi Wallet, vaya a la página de inicio. Luego haga clic en el botón 'Abrir Crosschain'. 
<p align="center">
<img src="/assets/WETH_1.png" width="400"/>
</p>

1. Haga clic en el menú.  
2. Haga clic en 'Conectado a:'

<p align="center">
<img src="/assets/WETH_2.png" width="400"/>
</p>  

Haga clic en 'Ethereum'. 
<p align="center">
<img src="/assets/WETH_3.png" width="400"/>
</p>  

1. Haga clic en 'Conectar Monedero'.
2. Haga clic en 'Wrap / Unwrap ETH' para cargar el widget Kyber.

<p align="center">
<img src="/assets/WETH_4.png" width="400"/>
</p>  

Ingrese el monto a transferir y luego marque los términos de acuerdo. Presione siguiente para continuar.  

<p align="center">
<img src="/assets/WETH_5.png" width="400"/>
</p>  

> Nota *** Asegúrese de tener suficiente ETH reservado para pagar las tarifas de transacción. 

Verifique la cantidad a intercambiar y luego haga clic en 'CONFIRMAR'.

<p align="center">
<img src="/assets/WETH_6.png" width="400"/>
</p>  

Haga clic en 'Confirmar' para finalizar la transacción o haga clic en 'Editar' para cambiar las tarifas de gas.  
<p align="center">
<img src="/assets/WETH_7.png" width="400"/>
</p>  

Opcionalmente, puede aumentar la tarifa para reducir el tiempo de espera. 
<p align="center">
<img src="/assets/WETH_8.png" width="400"/>
</p>  

Una vez confirmada y transmitida, se crea una identificación de transacción.  

<p align="center">
<img src="/assets/WETH_9.png" width="400"/>
</p>  

Desde la pantalla de Cross-Chain:
1. Haga clic en la lista desplegable.  
2. Elija WETH de la lista. 

<p align="center">
<img src="/assets/WETH_10.png" width="400"/>
</p>  

1. Ingrese la cantidad de WETH para transferir a través del bridge.  
2. Haga clic en 'Unlock/Desbloquear' para permitir que el permiso del contrato inteligente interactúe con su monedero.  

<p align="center">
<img src="/assets/WETH_11.png" width="400"/>
</p>  

> Nota *** Debido al intenso tráfico en Ethereum, se recomienda aumentar las tarifas del gas para reducir los tiempos de espera. 

Haga clic en 'Confirm/Confirmar' para finalizar o haga clic en 'Edit/Editar' para cambiar las tarifas de gas.  

<p align="center">
<img src="/assets/WETH_12.png" width="400"/>
</p>  

Dependiendo del tráfico de la red, la transacción puede tardar unos minutos en confirmarse. Si está atascado en la pantalla "Cargando ..." durante unos minutos, puede volver a cargar la página para verificar si está desbloqueada. Se recomienda que aumente la tarifa del gas a fast/rápido para reducir el tiempo de espera.

<p align="center">
<img src="/assets/WETH_13.png" width="400"/>
</p>  

Una vez desbloqueado:
1. Ingrese la cantidad de WETH que le gustaría transferir a Velas blockchain.
2. Haga clic en 'Transfer/Transferir' para continuar.

<p align="center">
<img src="/assets/WETH_14.png" width="400"/>
</p>  

Confirme la transacción y luego haga clic en 'Accept/Aceptar' para continuar.
<p align="center">
<img src="/assets/WETH_15.png" width="400"/>
</p>  

Haga clic en 'Confirmar' para finalizar o en 'Edit/Editar' para cambiar las tarifas de gas.
<p align="center">
<img src="/assets/WETH_16.png" width="400"/>
</p>  
</p> 
</details>
  
<details>
<summary>Transferring WETH on Velas back to Ethereum blockchain.</summary>  
<br>

Desde la página de cross-chain:  
1. Haga clic en el menú.
2. Haga clic en 'Conectado a:'

<p align="center">
<img src="/assets/WETH_17.png" width="400"/>
</p>  

Elija la red Velas.
<p align="center">
<img src="/assets/WETH_18.png" width="400"/>
</p>  

Haga clic en 'Connect/Conectar Wallet', luego haga clic en la lista desplegable y elija 'WETH'.   
<p align="center">
<img src="/assets/WETH_19.png" width="400"/>
</p>  

1. Ingrese la cantidad de WETH que se transferirá de regreso a la red Ethereum. 
2. Haga clic en 'Transfer/Transferir' para continuar. 

<p align="center">
<img src="/assets/WETH_20.png" width="400"/>
</p>  

Confirm transaction and click 'OK' to continue.  
<p align="center">
<img src="/assets/WETH_21.png" width="400"/>
</p>  

Espere a que se confirme la transacción. También puede hacer clic en la identificación de la transacción para realizar un seguimiento del progreso.
<p align="center">
<img src="/assets/WETH_22.png" width="400"/>
</p>  

1. Haz clic en el menú.
2. Haga clic en 'Conectado a:'.

<p align="center">
<img src="/assets/WETH_23.png" width="400"/>
</p>  

Elija la red Ethereum.
<p align="center">
<img src="/assets/WETH_24.png" width="400"/>
</p>  

Haga clic en 'Wrap / Unwrap ETH' para cargar el widget Kyber.
<p align="center">
<img src="/assets/WETH_25.png" width="400"/>
</p>  

Haga clic en el botón 'Swap/Cambiar' para que el 'Desde token' sea WETH. 
<p align="center">
<img src="/assets/WETH_26.png" width="400"/>
</p>  

Ingrese la cantidad de WETH para convertir a ETH. Marque la casilla de los términos del acuerdo y haga clic en 'Siguiente'.  
<p align="center">
<img src="/assets/WETH_27.png" width="400"/>
</p>  

Verifique la transacción y luego haga clic en 'APPROVE/APROBAR' para continuar.  
<p align="center">
<img src="/assets/WETH_28.png" width="400"/>
</p>  

Haga clic en 'Confirm/Confirmar' para finalizar o en 'Edit/Editar' para cambiar el precio del gas. 
<p align="center">
<img src="/assets/WETH_29.png" width="400"/>
</p>  

Haga clic en 'CONFIRM/CONFIRMAR' para finalizar la transacción. 
<p align="center">
<img src="/assets/WETH_30.png" width="400"/>
</p>  


</p> 
</details>
  

