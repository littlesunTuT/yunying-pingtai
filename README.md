Vue 3 + TypeScript + Vite
推荐的 IDE 设置
VS Code + Volar（并禁用 Vetur）+ TypeScript Vue 插件（Volar）。
.vueTS 中导入的类型支持
.vue默认情况下，TypeScript 无法处理导入的类型信息，因此我们tsc用 CLI替换了vue-tsc类型检查。在编辑器中，我们需要TypeScript Vue 插件 (Volar)来使 TypeScript 语言服务能够识别.vue类型。
