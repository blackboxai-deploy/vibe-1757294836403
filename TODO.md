# TODO - Sistema de Gestão Educacional BNCC-SAEB

## ✅ Etapas de Implementação

### 1. Estrutura Base e Layout
- [ ] Criar layout principal com navegação sidebar
- [ ] Configurar roteamento das páginas principais
- [ ] Implementar tema e estilos base
- [ ] Criar componentes de navegação

### 2. Dados Base (BNCC e SAEB)
- [ ] Criar banco de dados BNCC com habilidades por disciplina
- [ ] Implementar estrutura SAEB para Português e Matemática
- [ ] Configurar sistema de storage local

### 3. Módulo de Planejamento BNCC
- [ ] Interface de seleção de disciplina e ano
- [ ] Formulário de criação de planos de aula
- [ ] Templates pré-configurados
- [ ] Sistema de objetivos de aprendizagem

### 4. Geração de Provas com IA
- [ ] API para geração de questões automáticas
- [ ] Interface de configuração de provas
- [ ] Sistema de seleção de habilidades SAEB
- [ ] Geração de gabarito automático
- [ ] Exportação em PDF

### 5. Correção por Câmera
- [ ] Interface de captura de imagem
- [ ] Sistema OCR para leitura de cartão resposta
- [ ] Algoritmo de correção automática
- [ ] Interface de confirmação/edição manual

### 6. Análise e Relatórios
- [ ] Dashboard com métricas principais
- [ ] Gráficos de desempenho por habilidade
- [ ] Relatórios de defasagem
- [ ] Sistema de recomendações pedagógicas

### 7. Finalização
- [ ] **AUTOMATIC**: Process placeholder images (placehold.co URLs) → AI-generated images
  - This step executes automatically when placeholders are detected
  - No manual action required - system triggers automatically
  - Ensures all images are ready before testing
- [ ] Testes de funcionalidade
- [ ] Otimizações de performance
- [ ] Documentação final

## 🎯 Funcionalidades Principais
- ✅ Planejamento de aulas baseado na BNCC
- ✅ Criação de provas por IA com habilidades SAEB  
- ✅ Correção automática via leitura de cartão resposta
- ✅ Gráficos de análise de defasagem por habilidade
- ✅ Interface responsiva e moderna
- ✅ PWA para uso mobile otimizado

## 📱 Tecnologias
- Next.js 15 + TypeScript
- Tailwind CSS + shadcn/ui
- Recharts para gráficos
- Camera API + Canvas para OCR
- jsPDF para geração de PDFs
- Local Storage para dados