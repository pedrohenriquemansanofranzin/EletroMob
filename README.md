# EletroMob - Sistema de Aluguel de Veículos Elétricos

## 📱 Sobre o Projeto

EletroMob é uma plataforma completa para aluguel de bicicletas e patinetes elétricos para uso urbano. O sistema oferece uma experiência intuitiva desde a navegação inicial até a conclusão do pagamento.

## 🗂️ Arquivos do Projeto

1. **eletromob.html** - Landing page principal
2. **cadastro.html** - Página de cadastro e login
3. **mapa.html** - Mapa interativo com veículos disponíveis
4. **selecao-veiculo.html** - Página de confirmação do veículo
5. **pagamento.html** - Página de checkout e pagamento

## 🚀 Como Usar

### Fluxo Completo do Usuário:

1. **Página Inicial (eletromob.html)**
   - Abra este arquivo primeiro
   - Conheça os serviços oferecidos
   - Clique em "Criar Conta" ou "Entrar" para começar

2. **Cadastro/Login (cadastro.html)**
   - Crie uma nova conta ou faça login
   - Opções de login social (Google, Facebook)
   - Após login, você será redirecionado para o mapa

3. **Mapa Interativo (mapa.html)**
   - Visualize todos os veículos disponíveis no mapa
   - Filtre por tipo: bicicletas ou patinetes
   - Veja detalhes de cada veículo (bateria, distância)
   - Veja estações de devolução marcadas no mapa
   - Clique em "Alugar Agora" para selecionar um veículo

4. **Seleção de Veículo (selecao-veiculo.html)**
   - Confirme os detalhes do veículo escolhido
   - Escolha seu plano de pagamento:
     - Pague por uso (15 minutos)
     - Por hora
     - Passe diário
   - Visualize o QR Code para desbloqueio
   - Leia as regras de segurança
   - Clique em "Confirmar e Pagar"

5. **Pagamento (pagamento.html)**
   - Escolha o método de pagamento:
     - Cartão de crédito
     - Cartão de débito
     - PIX
     - Saldo da carteira
   - Use cartões salvos ou adicione um novo
   - Aplique códigos promocionais (experimente: BEMVINDO ou PRIMEIRAVIAGEM)
   - Confirme o pagamento
   - Receba o código de desbloqueio

## 🎯 Recursos Principais

### Landing Page
✅ Design moderno e responsivo
✅ Seção de veículos com preços
✅ Como funciona (4 passos)
✅ Vantagens do serviço
✅ Links para download do app
✅ Footer completo com informações

### Cadastro/Login
✅ Formulário de cadastro completo
✅ Validação de senha
✅ Formatação automática de CPF e telefone
✅ Login social (Google, Facebook)
✅ Design split-screen atraente

### Mapa Interativo
✅ Mapa real usando Leaflet.js e OpenStreetMap
✅ Marcadores customizados para cada tipo de veículo
✅ Estações de devolução
✅ Filtros por tipo de veículo
✅ Lista lateral com veículos disponíveis
✅ Detalhes de bateria e distância
✅ Localização do usuário

### Seleção de Veículo
✅ Visualização detalhada do veículo
✅ Informações de bateria, velocidade e autonomia
✅ Três opções de plano
✅ QR Code para desbloqueio
✅ Regras de segurança
✅ Preços dinâmicos

### Pagamento
✅ Múltiplos métodos de pagamento
✅ Cartões salvos
✅ Código promocional
✅ Resumo do pedido
✅ Barra de progresso
✅ Modal de confirmação com código de desbloqueio
✅ Validação de formulário

## 💡 Funcionalidades Especiais

### Códigos Promocionais
- **BEMVINDO** - R$ 2,00 de desconto
- **PRIMEIRAVIAGEM** - R$ 2,00 de desconto

### Dados de Teste

**Veículos Disponíveis:**
- BK001, BK002, BK003 (Bicicletas)
- SC001, SC002, SC003 (Patinetes)

**Cartão Salvo:**
- Final: •••• 4532
- Tipo: Visa

## 📱 Responsividade

Todos os arquivos são totalmente responsivos e funcionam perfeitamente em:
- 💻 Desktop (1920px+)
- 💻 Laptop (1024px - 1920px)
- 📱 Tablet (768px - 1024px)
- 📱 Mobile (320px - 768px)

## 🎨 Tecnologias Utilizadas

- **HTML5** - Estrutura semântica
- **CSS3** - Estilização moderna com gradientes e animações
- **JavaScript Vanilla** - Interatividade e validações
- **Leaflet.js** - Biblioteca de mapas interativos
- **OpenStreetMap** - Dados de mapa gratuitos

## 🔧 Personalização

### Cores Principais
```css
Primária: #667eea (Azul/Roxo)
Secundária: #764ba2 (Roxo escuro)
Sucesso: #4CAF50 (Verde)
Alerta: #FF9800 (Laranja)
```

### Preços
Os preços podem ser facilmente ajustados nos arquivos:
- Landing page: seção de veículos
- Seleção de veículo: objeto `vehicles`
- Mapa: array `vehicles`

## 📝 Notas Importantes

1. **Armazenamento Local**: O sistema usa `localStorage` para manter informações entre páginas
2. **Mapa**: Requer conexão com internet para carregar os tiles do OpenStreetMap
3. **Geolocalização**: O mapa solicita permissão para mostrar a localização do usuário
4. **Simulação**: Este é um protótipo - funções de backend precisam ser implementadas

## 🚀 Próximos Passos (Backend)

Para tornar este sistema funcional, você precisará adicionar:
- [ ] Sistema de autenticação real
- [ ] API para gerenciar veículos
- [ ] Gateway de pagamento
- [ ] Sistema de tracking GPS dos veículos
- [ ] Banco de dados
- [ ] Notificações push
- [ ] Sistema de suporte

## 📞 Informações de Contato

- Email: contato@eletromob.com.br
- Telefone: (11) 1234-5678
- Localização: São Paulo, SP

---

**Desenvolvido para demonstração de conceito do sistema EletroMob** 🚲⚡
