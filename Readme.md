# Installation et configuration du WSL

## Prérequis

- Windows 10 ou 11

## Installation

- Dans la barre de recherche windows, cherchez et ouvrez ```Fonctionnalités de Windows```.

    <details>
      <summary>Illustration</summary>
    
    ![img_11.png](ressources/enable_windows_functionality.png)
    
    </details>


- Vérifier que le ```Sous-système Windows pour linux``` ainsi que ``l'HyperViseur`` sont bien activé.  
S'il n'est pas activé, veuillez cocher la case à gauche et cliquer sur **Ok** (Redémarrez votre PC lorsque windows vous le proposera).  

    <details>
      <summary>Illustration</summary>
    
    ![img.png](ressources/enable_windows_functionality_2.png)
    
    </details>


- Dans la barre de recherche windows, cherchez et ouvrez ```powershell``` en mode **Administrateur**.
    <details>
      <summary>Illustration</summary>
    
    ![img_14.png](ressources/powershell.png)
    
    </details>


- Exécutez la commande suivante : ``wsl --install``
    <details>
      <summary>Illustration</summary>
    
    ![img_4.png](ressources/wsl_install_cmd.png)
    ![img_8.png](ressources/wsl_install_output.png)
    </details>


- Ouvrez l'application Ubuntu
  <details>
      <summary>Illustration</summary>

    ![img.png](ressources/open_ubuntu.png)
    </details>


- La première fois, vous devez créer un utilisateur. Saisissez le nom d'utilisateur et le mot de passe de votre choix.  
(**Au niveau du mot de passe, il est normal que rien n'apparaisse lors de la saisie, mais vos touches sont bien prises en compte**)
    <details>
      <summary>Illustration</summary>
    
    ![img_15.png](ressources/create_ubuntu_user.png)
    ![img_16.png](ressources/ubuntu_first_view.png)
    </details>

**Félicitations ! Vous pouvez à présent accéder au sous système windows pour linux (WSL) quand vous le souhaitez.**

## Comment accéder aux fichiers depuis l'explorer Windows ?

- Ouvrez l'explorateur de fichier et saisissez la route suivante ``\\wsl$`` et appuyez sur ``Entrée``
    <details>
      <summary>Illustration</summary>
    
    ![img_9.png](ressources/wsl_path_windows_explorer.png)
    </details>


- Sélectionnez ensuite le dossier ``Ubuntu``
    <details>
      <summary>Illustration</summary>
    
    ![img_10.png](ressources/ubuntu_path_windows_explorer.png)
    </details>
    


