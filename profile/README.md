# Nodus

**Nodus** é uma arquitetura moderna baseada em **Web Components**, projetada para simplificar e padronizar o desenvolvimento frontend. Dividido em dois pacotes principais — [`@nodusjs/std`](https://www.npmjs.com/package/@nodusjs/std) e [`@nodusjs/x`](https://www.npmjs.com/package/@nodusjs/x) — o Nodus oferece uma solução completa para criar e utilizar componentes reutilizáveis de forma eficiente.

## 🔍 Visão Geral

O Nodus visa resolver os desafios comuns enfrentados por equipes de desenvolvimento frontend, como a complexidade crescente do código, dificuldades na manutenção e a falta de padronização. Com uma abordagem modular e orientada a componentes, o Nodus promove:

* **Simplicidade**: Facilita a criação e utilização de componentes.
* **Reusabilidade**: Componentes independentes e reutilizáveis.
* **Padronização**: Promove boas práticas e consistência no desenvolvimento.
* **Eficiência**: Reduz o tempo de desenvolvimento e manutenção.

## 🏗️ Estrutura do Projeto

### `@nodusjs/std` (Standard)

O `@nodusjs/std` é o núcleo da arquitetura Nodus. Ele fornece as ferramentas e padrões necessários para criar seus próprios Web Components personalizados, promovendo uma base sólida para o desenvolvimento frontend.

### `@nodusjs/x` (Components)

O `@nodusjs/x` é uma biblioteca de componentes prontos para uso, construídos com base no `@nodusjs/std`. Esses componentes podem ser facilmente integrados em qualquer projeto frontend, oferecendo uma solução rápida e eficiente para desenvolver interfaces de usuário.

## 📦 Instalação

### Usando NPM

```bash
npm install @nodusjs/x
```

### Usando Yarn

```bash
yarn add @nodusjs/x
```

### Usando BAM

```bash
bam install @nodusjs/x
```

### Usando CDN (JavaScript)

```html
<script src="https://cdn.jsdelivr.net/npm/@nodusjs/x@latest/dist/x.js" async></script>
```

### Usando CDN (CSS)

```html
<link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/@nodusjs/x@latest/dist/x.css">
```

> 💡 **Dica**: Para ver exemplos funcionando, acesse o playground no CodePen: [https://codepen.io/nodusjs](https://codepen.io/nodusjs)

## 🧪 Uso

Após a instalação, você pode importar e utilizar os componentes do `@nodusjs/x` em seu projeto:

```js
import '@nodusjs/x';
```

## 📚 Documentação

Para mais detalhes sobre os componentes disponíveis e exemplos de uso, consulte a [documentação completa](https://github.com/nodusjs/x#documentação).

## 🤝 Contribuindo

Contribuições são bem-vindas! Se você deseja contribuir com o Nodus, siga as etapas abaixo:

1. Fork este repositório.
2. Crie uma branch com sua feature:

   ```bash
   git checkout -b minha-feature
   ```
3. Commit suas alterações:

   ```bash
   git commit -m 'Adiciona minha feature'
   ```
4. Push para a branch:

   ```bash
   git push origin minha-feature
   ```
5. Abra um Pull Request.

## 📄 Licença

Este projeto está licenciado sob a Licença MIT — veja o arquivo [LICENSE](./LICENSE) para detalhes.
