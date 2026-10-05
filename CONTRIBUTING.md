# 🤝 Guia de Contribuição

Obrigado por considerar contribuir para o **DRZ7 Optimizer Atualizador**! 

## 📋 Código de Conduta

Somos dedicados a manter um ambiente respeitoso e inclusivo para todos.

## 🐛 Reportar Bugs

Antes de criar um relatório de bug, verifique se o problema já foi reportado. Ao criar um bug report:

1. **Use um título descritivo**
2. **Descreva o comportamento observado**
3. **Descreva o comportamento esperado**
4. **Inclua screenshots se aplicável**
5. **Mencione sua versão e sistema operacional**
6. **Inclua logs de erro**

## 💡 Sugerir Melhorias

Sugestões são bem-vindas! Para sugerir uma melhoria:

1. Use um título claro
2. Descreva a solução proposta
3. Liste possíveis alternativas
4. Adicione exemplos se possível

## 🔄 Pull Requests

1. Fork o repositório
2. Crie uma branch (`git checkout -b feature/sua-feature`)
3. Commit com mensagens claras
4. Push para a branch
5. Abra um Pull Request

### Padrão de Commits

```
type(scope): descrição breve

Descrição mais detalhada se necessário.

Fixes #123
```

**Types:**
- `feat:` Nova funcionalidade
- `fix:` Correção de bug
- `docs:` Documentação
- `style:` Formatação (sem mudanças de código)
- `refactor:` Refatoração
- `test:` Testes
- `chore:` Tarefas de manutenção

**Exemplo:**
```
feat(updater): adicionar verificação de hash

Implementa validação SHA-256 para arquivos baixados
para aumentar segurança.

Fixes #42
```

## ✅ Checklist Antes de Enviar PR

- [ ] Código segue os padrões do projeto
- [ ] Testes adicionados/atualizados
- [ ] Documentação atualizada
- [ ] Sem conflitos com a branch principal
- [ ] Mensagens de commit claras
- [ ] Sem arquivos desnecessários

## 📚 Desenvolvimento

### Clonar e Configurar
```bash
git clone https://github.com/MateusDrz7/otimizador-atualizador.git
cd otimizador-atualizador
```

### Dependências
Consulte [SETUP.md](SETUP.md) para configuração.

### Testes
```bash
# Executar testes
npm test

# Cobertura
npm run test:coverage
```

## 🎯 Áreas de Contribuição

- 🐛 Correção de bugs
- 📖 Melhoria de documentação
- ✨ Novas features
- 🧪 Testes
- 🎨 UI/UX

## ❓ Dúvidas?

- 📖 Leia a [Documentação](docs/)
- 💬 Abra uma [Discussion](https://github.com/MateusDrz7/otimizador-atualizador/discussions)
- 🐛 Crie uma [Issue](https://github.com/MateusDrz7/otimizador-atualizador/issues)

---

Obrigado por contribuir! 🙏
