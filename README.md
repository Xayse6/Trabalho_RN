# 📱 LocalShop

Projeto desenvolvido por **Guilherme Augusto Trindade da Luz** para a disciplina de **Programação para Dispositivos Móveis**, orientada pelo professor **James William Zeri de Campos**.

O aplicativo tem como objetivo listar e cadastrar estabelecimentos locais, permitindo visualizar informações detalhadas sobre cada local.

---

# 🚀 Tecnologias Utilizadas

- React Native
- TypeScript
- Expo
---

# 📂 Estrutura do Projeto

```bash
src/
 ├── @types/
 │    └── loja.ts
 │
 ├── components/
 │    ├── LojaCard.tsx
 │    └── StyleLojaCard.ts
 │
 ├── data/
 │    └── mockData.ts
 │
 ├── hooks/
 │    ├── useCadastroLoja.ts
 │    └── useLojas.ts
 │
 ├── screens/
 │    ├── cadastroLoja/
 │    │    ├── CadastroLoja.tsx
 │    │    └── CadastroLojaStyles.ts
 │    │
 │    ├── details/
 │    │    ├── LojaDetalhes.tsx
 │    │    └── StyleHome.ts
 │    │
 │    ├── home/
 │    │    ├── HomeScreen.tsx
 │    │    └── useLojas.ts
 │    │
 │    └── services/
 │         └── api.ts
 │
 ├── App.tsx
 │
 └── index.ts

