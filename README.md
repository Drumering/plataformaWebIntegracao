# plataformaWebIntegracao

## Deploy of versioning techniques

### Git clone with SSH Key

#### Generate the ssh key:

- ssh-keygen -t rsa -b 4096 -C "your_email@example.com"
  - Use your email
- Locale the key, usually in, then copy the entire content, usually init with *ssh-rsa*:
  - /home/you/.ssh/id_rsa.pub

#### Now navigate on menu to add this key
- Access the Settings Menu

  ![Imgur](https://i.imgur.com/G5JFJhv.png)
  
- Access the Personal Settings menu and click on SSH and GPG Keys

  ![Imgur](https://i.imgur.com/XoMBJUv.png)

- Then click on *New ssh key* and paste the content of the last step

  ![Imgur](https://i.imgur.com/afVw5tO.png)

### Cloning a repository

- Access the home page of your repository and click on *Clone or Download*
  
  ![Imgur](https://i.imgur.com/dsU4G9W.png)

- Copy the code where say *Clone with SSH*

  ![Imgur](https://i.imgur.com/OEu42aE.png)

#### Conslusion

Now you can clone, add, commit and push your code without need insert your credencials, **on this machine**.