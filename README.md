# Sample Hardhat Project

This project demonstrates a basic Hardhat use case. It comes with a sample contract, a test for that contract, and a Hardhat Ignition module that deploys that contract.

Try running some of the following tasks:

```shell
npx hardhat help
npx hardhat test
REPORT_GAS=true npx hardhat test
npx hardhat node
npx hardhat ignition deploy ./ignition/modules/Lock.ts
```

En el entorno de desarrollo de smart contracts de tu preferencia (Hardhat o Foundry), crea un repositorio donde vas a desplegar un token ERC-20 o un ERC-721 (NFT). Envía el enlace del contrato desplegado en Arbitrum Sepolia y el enlace del repositorio.

Tienes hasta el 25 de Junio para entregar este proyecto.

Ten en cuenta los siguientes pasos: 

    Crea el Repositorio en GitHub
    Descarga el contrato de tu preferencia del Wizard de Open Zepellin
    https://wizard.openzeppelin.com/
    Crea tu proyecto en Hardhat o Foundry dentro del repositorio.
        No olvides configurar tu entorno de desarrollo para Arbitrum Sepolia
        Recuerda que puedes reclamar tokens de Arbitrum Sepolia en https://educateth-faucet.vercel.app/
            No olvides registrar tu billetera si no lo has hecho 
            https://172-105-105-210.ip.linodeusercontent.com/mod/feedback/view.php?id=174
        Ten cuidado con exponer la llave privada de tu billetera en el repositorio. Crea un .gitignore en tu repositorio.
    Crea el contrato. 
    Compila el contrato.
    Realiza dos pruebas automáticas en la carpeta test.
    Desplegar el contrato en Arbitrum Sepolia.
    Verificar el contrato.
Comparte tus dudas en el canal de Discord para resolverlas junto a tus compañer@s de Curso. 