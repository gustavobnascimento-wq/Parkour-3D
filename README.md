# 🎮 Parkour 3D Web Game

![Three.js](https://img.shields.io/badge/Three.js-r128-black?style=for-the-badge&logo=three.js)
![JavaScript](https://img.shields.io/badge/JavaScript-ES6+-yellow?style=for-the-badge&logo=javascript)
![WebGL](https://img.shields.io/badge/WebGL-3D-red?style=for-the-badge&logo=webgl)

Um jogo interativo de plataforma e parkour 3D desenvolvido para navegador utilizando **Three.js**. O jogador controla um robô por quatro estágios de dificuldade crescente, enfrentando saltos de precisão, plataformas móveis, plataformas caducas e feixes de laser mortais[cite: 1, 2].

---

## 🚀 Funcionalidades

- **Física & Colisões:** Detecção precisa de plataformas rígidas, móveis e que desmoronam após contato[cite: 1].
- **Perigos Dinâmicos:** Lasers em movimento no padrão alternado (3-2-3-2-3) no 4º estágio com detecção de contato instantânea via `Box3`[cite: 2, 4].
- **Shift Lock & Câmera 3D:** Controle de câmera em terceira pessoa usando `OrbitControls` e travamento de mira com a tecla `Shift`[cite: 1].
- **Animações Suaves:** Renderização GLTF com animações integradas de corrida, pulo e estado inativo[cite: 1].

---

## 🎮 Controles do Jogo

| Tecla / Comando | Ação |
| :--- | :--- |
| `W` `A` `S` `D` / `Setas` | Movimentar o personagem |
| `Espaço` | Saltar |
| `Shift` | Ativar/Desativar o Shift Lock (Mira fixa) |
| `Scroll do Mouse` | Aproximar/Afastar a câmera (Zoom) |

---

## ⚡ Backdoor & Modo Admin

Digite a palavra secreta `batmangg` enquanto estiver no **Menu Principal** para liberar as permissões de administrador[cite: 2, 5]:

- **Desbloqueio Total:** Libera instantaneamente todos os 4 estágios do jogo[cite: 2, 5].
- **Modo Voo:** Pressione a barra de `Espaço` duas vezes rapidamente para alternar o modo de voo livre[cite: 2, 5].
  - `Espaço`: Subir no ar[cite: 2]
  - `Ctrl` ou `C`: Descer no ar[cite: 2]

---

## 🛠️ Tecnologias Utilizadas

- **Three.js (r128):** Biblioteca gráfica 3D[cite: 1].
- **GLTFLoader:** Carregamento e renderização do modelo 3D dinâmico[cite: 1].
- **HTML5 / CSS3 / JavaScript Vanilla:** Estruturação, interface gráfica HUD e lógica do jogo[cite: 1].

---

## 📦 Como Executar

1. Descarrega os ficheiros do projeto ou clona este repositório:
   ```bash
   git clone [https://github.com/SEU-USUARIO/Parkour-3D.git](https://github.com/SEU-USUARIO/Parkour-3D.git)
