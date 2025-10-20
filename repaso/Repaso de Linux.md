# -- MANUAL PRACTICO DE LINUX --

[TOC]



## -CAPITULO 2-



### 2.1- Estructura de Directorios

<img src="C:/Users/2dawv05/AppData/Roaming/Typora/typora-user-images/image-20250929155745905.png" alt="image-20250929155745905" style="zoom: 59%;" />

### 2.2- Visualización, Creación y Cambio de Directorios

```bash
 $pwd
```

<img src="C:/Users/2dawv05/AppData/Roaming/Typora/typora-user-images/image-20250929160202019.png" alt="image-20250929160202019" style="zoom: 80%;" />clear



```bash
ls
```

<img src="C:/Users/2dawv05/AppData/Roaming/Typora/typora-user-images/image-20250929163730346.png" alt="image-20250929163730346" style="zoom:80%;" />

```bash
cd
```

<img src="C:/Users/2dawv05/AppData/Roaming/Typora/typora-user-images/image-20250929164105521.png" alt="image-20250929164105521" style="zoom:80%;" />

```bash
mkdir
```

<img src="C:/Users/2dawv05/AppData/Roaming/Typora/typora-user-images/image-20250929164211170.png" alt="image-20250929164211170" style="zoom:80%;" />

### 2.3- Visualización de Ficheros

```bash
cat
```

<img src="C:/Users/2dawv05/AppData/Roaming/Typora/typora-user-images/image-20250929164316732.png" alt="image-20250929164316732" style="zoom:80%;" />

```bash
$more
```

<img src="C:/Users/2dawv05/AppData/Roaming/Typora/typora-user-images/image-20250929164338546.png" alt="image-20250929164338546" style="zoom:80%;" />

```bash
$less
```

<img src="C:/Users/2dawv05/AppData/Roaming/Typora/typora-user-images/image-20250929164408640.png" alt="image-20250929164408640" style="zoom:80%;" />

<img src="C:/Users/2dawv05/AppData/Roaming/Typora/typora-user-images/image-20250929164435975.png" alt="image-20250929164435975" style="zoom:80%;" />

```bash
$head
```

<img src="C:/Users/2dawv05/AppData/Roaming/Typora/typora-user-images/image-20250929164454425.png" alt="image-20250929164454425" style="zoom:80%;" />

```bash
$tail
```

<img src="C:/Users/2dawv05/AppData/Roaming/Typora/typora-user-images/image-20250929164517479.png" alt="image-20250929164517479" style="zoom:80%;" />

### 2.4- Edición de Ficheros

```bash
$nano
```

<img src="C:/Users/2dawv05/AppData/Roaming/Typora/typora-user-images/image-20250929163350871.png" alt="image-20250929163350871" style="zoom:80%;" />

<img src="C:/Users/2dawv05/AppData/Roaming/Typora/typora-user-images/image-20250929163621285.png" alt="image-20250929163621285" style="zoom:80%;" />



## -CAPITULO 3-



### 3.1- Copia y Borrado de Ficheros



```bash
cp 
```

<img src="./Repaso%20de%20Linux.assets/image-20250929165829609.png" alt="image-20250929165829609" style="zoom:80%;" />

```bash
mv
```

<img src="./Repaso%20de%20Linux.assets/image-20250929170030440.png" alt="image-20250929170030440" style="zoom:80%;" />

```bash
rm
```

<img src="./Repaso%20de%20Linux.assets/image-20250929170232744.png" alt="image-20250929170232744" style="zoom:80%;" />

### 3.2- Copia y Borrado de Directorios



```bash
cp -R
```

<img src="./Repaso%20de%20Linux.assets/image-20250929170554130.png" alt="image-20250929170554130" style="zoom:67%;" />



## -CAPITULO 4-



### 4.1- Permisos

<img src="./Repaso%20de%20Linux.assets/image-20250929171155838.png" alt="image-20250929171155838" style="zoom:50%;" />



```bash
ls -l 
```

<img src="./Repaso%20de%20Linux.assets/image-20250929171117254.png" alt="image-20250929171117254" style="zoom:67%;" />

### 4.2- Pertenencias



```bash
$whoami
```

<img src="./Repaso%20de%20Linux.assets/image-20250929171422076.png" alt="image-20250929171422076" style="zoom:80%;" />

```bash
$groups
```

<img src="./Repaso%20de%20Linux.assets/image-20250929171511238.png" alt="image-20250929171511238" style="zoom:80%;" />

### 4.3- Gestión de Grupos



```bash
$groupadd
```

<img src="./Repaso%20de%20Linux.assets/image-20250929171730051.png" alt="image-20250929171730051" style="zoom:80%;" />

```bash
$groupmod
```

<img src="./Repaso%20de%20Linux.assets/image-20250929171953516.png" alt="image-20250929171953516" style="zoom:80%;" />

```bash
$groupdel
```

<img src="./Repaso%20de%20Linux.assets/image-20250929172356897.png" alt="image-20250929172356897" style="zoom:80%;" />

### 4.4- Gestión de Usuarios



```bash
sudo bash
```

<img src="./Repaso%20de%20Linux.assets/image-20251002160308471.png" alt="image-20251002160308471" style="zoom: 80%;" />

```bash
$adduser
```

<img src="./Repaso%20de%20Linux.assets/image-20251002160632138.png" alt="image-20251002160632138" style="zoom:80%;" />



### 4.5- Cambio de Grupo y Dueño

<img src="./Repaso%20de%20Linux.assets/image-20251002162233864.png" alt="image-20251002162233864" style="zoom:80%;" />



```bash
chmod
```

<img src="./Repaso%20de%20Linux.assets/image-20251002160934626.png" alt="image-20251002160934626" style="zoom:80%;" />

```baSH
chown
```

<img src="./Repaso%20de%20Linux.assets/image-20251002161059796.png" alt="image-20251002161059796" style="zoom:80%;" />

```bash
$chgrp
```

<img src="./Repaso%20de%20Linux.assets/image-20251002161501673.png" alt="image-20251002161501673" style="zoom:80%;" />



# -- FINAL DEL DOCUMENTO --