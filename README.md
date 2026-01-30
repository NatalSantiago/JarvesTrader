![Logo Jarve's Trader](JarvesTrader01.png =100x100)

🤖 Jarve's Trader - Expert Advisor para MetaTrader 5
<div align="center">

Sua Estratégia de Trading com Transparência e Resultados Reais

"Tecnologia que entende o mercado, honestidade que valoriza seu capital"

https://img.shields.io/badge/Expert_Advisor-MQL5-blue
https://img.shields.io/badge/Platform-MetaTrader%25205-green
https://img.shields.io/badge/Version-2.0.0-brightgreen
https://img.shields.io/badge/License-MIT-yellow
https://img.shields.io/badge/Language-Portuguese%2520(BR)-red

Sistema Automatizado com Machine Learning e Gestão Inteligente de Risco

https://img.shields.io/badge/Download-Latest_Release-success
https://img.shields.io/badge/WhatsApp-Suporte_24h-25D366
https://img.shields.io/badge/Email-Contato%2520R%C3%A1pido-blue

</div>
---

## 📑 Índice

- [Visão Geral](#-visão-geral)
- [Recursos Principais](#-recursos-principais)
- [Pré-requisitos](#-pré-requisitos)
- [Instalação Rápida](#-instalação-rápida)
- [Configuração Detalhada](#-configuração-detalhada)
- [Estratégias de Trading](#-estratégias-de-trading)
- [Machine Learning](#-machine-learning)
- [Gestão de Risco](#-gestão-de-risco)
- [Análise Fundamental](#-análise-fundamental)
- [Backtesting](#-backtesting)
- [Otimização](#-otimização)
- [FAQ](#-faq-perguntas-frequentes)
- [Suporte](#-suporte)
- [Contribuição](#-contribuição)
- [Licença](#-licença)
- [Apoio ao Projeto](#-apoio-ao-projeto)

---

## 🎯 Visão Geral

### O que é o Jarve´s Trader?

O **Jarve´s Trader** é um Expert Advisor (robô de trading) avançado desenvolvido para a plataforma MetaTrader 5. Ele combina técnicas tradicionais de análise de price action com algoritmos modernos de Machine Learning para identificar oportunidades de trading com alta probabilidade de sucesso.

### Objetivos do Projeto

1. **Automatização Inteligente**: Eliminar a emocionalidade do trading através de algoritmos objetivos
2. **Aprendizado Contínuo**: Sistema que evolui com o mercado através de ML
3. **Gestão de Risco Robusta**: Proteção de capital como prioridade máxima
4. **Acessibilidade**: Tradução completa para português e suporte à comunidade BR

### ⚠️ Aviso Importante

**Este software é fornecido para fins educacionais e de pesquisa.** Trading no mercado financeiro envolve riscos significativos de perda de capital. Você é o único responsável por suas decisões de trading. Teste exaustivamente em conta DEMO antes de considerar uso real.

---

## ✨ Recursos Principais

### 🤖 Machine Learning Avançado
- **5 algoritmos de ML diferentes**
- Reconhecimento automático de padrões
- Score de confiança em tempo real
- Aprendizado adaptativo ao mercado

### 📊 Análise Técnica Completa
- 12 padrões de candlestick detectados
- Múltiplos indicadores técnicos (EMA, RSI, ATR)
- Análise multi-timeframe
- Detecção de tendências

### 🛡️ Gestão de Risco Inteligente
- 3 tipos de gestão de risco
- Trailing stop dinâmico
- Limite diário de trades
- Fechamento automático sexta-feira

### 🔄 Sistema Anti-Duplicação
- Validação dupla de trades
- Prevenção de over-trading
- Proteção contra martingale

### 📈 Análise Fundamental
- Filtro de notícias econômicas
- Calendário econômico integrado
- Horários otimizados de trading

### 🌐 Interface Amigável
- Totalmente em português
- Configuração intuitiva
- Logs detalhados
- Painel de monitoramento

---

## 📋 Pré-requisitos

### Requisitos Técnicos Mínimos

| Componente | Requisito Mínimo | Recomendado |
|------------|------------------|-------------|
| **Sistema Operacional** | Windows 10 64-bit | Windows 11 |
| **MetaTrader 5** | Versão 5.0 | Última versão |
| **Processador** | Dual-core 2.0 GHz | Quad-core 3.0 GHz+ |
| **Memória RAM** | 4 GB | 8 GB+ |
| **Armazenamento** | 1 GB livre | 10 GB+ |
| **Conexão Internet** | 10 Mbps | 50 Mbps+ |

### Contas Necessárias
1. **Conta DEMO**: Para testes iniciais (obrigatório)
2. **Conta Real**: Opcional, somente após testes completos
3. **Broker**: Qualquer broker compatível com MT5

### Conhecimento Recomendado
- Básico de trading
- Familiaridade com MetaTrader 5
- Compreensão de risco financeiro
- Noções de análise técnica

---

## 🚀 Instalação Rápida

### Download do EA

**[⬇️ BAIXAR VERSÃO MAIS RECENTE](https://github.com/NatalSantiago/Jarves-Trader/releases/latest)**

### Passo-a-Passo em 5 Minutos

#### 1. Baixar e Extrair
```bash
1. Clique no link acima para baixar
2. Extraia o arquivo ZIP em uma pasta
3. Você verá os arquivos:
   - JarvesTrader.mq5 (EA principal)
   - TreinadorML.mq5 (Opcional)
   - PriceActionPatterns.mqh (Biblioteca)
```

#### 2. Copiar para o MT5
```bash
1. Abra o MetaTrader 5
2. Menu: Arquivo → Abrir Pasta de Dados
3. Navegue até: MQL5/Experts/
4. Copie os arquivos .mq5 para esta pasta
5. Copie arquivos .mqh para: MQL5/Include/
```

#### 3. Compilar o EA
```bash
1. No MT5, pressione F4 para abrir o MetaEditor
2. Abra o arquivo JarvesTrader.mq5
3. Pressione F7 para compilar
4. Verifique se não há erros (deve aparecer "0 errors")
```

#### 4. Configurar no Gráfico
```bash
1. Volte ao MT5 e abra um gráfico (ex: EURUSD H1)
2. Na Janela de Navegação, vá em "Expert Advisors"
3. Arraste "Jarve's Trader" para o gráfico
4. Configure os parâmetros (veja próxima seção)
5. Clique em "OK" para ativar
```

#### 5. Verificar Funcionamento
```bash
1. Verifique o log em: Experts (Ctrl+T)
2. Deve aparecer "Jarve's Trader inicializado"
3. O EA começará a analisar o mercado
4. Pronto! O sistema está operacional
```

---

## ⚙️ Configuração Detalhada

### Parâmetros de Configuração

#### Seção: CONFIGURAÇÕES GERAIS
| Parâmetro | Valor Padrão | Descrição |
|-----------|--------------|-----------|
| `Nome_Expert` | "Jarve's Trader" | Identificação do EA |
| `Tamanho_Lote` | 0.1 | Volume padrão das operações |
| `Numero_Magico` | 2024 | ID único para identificação |
| `Deslizamento` | 3 | Slippage máximo permitido |

#### Seção: ANÁLISE TÉCNICA
| Parâmetro | Valor Padrão | Descrição |
|-----------|--------------|-----------|
| `Timeframe_Analise` | PERIOD_H1 | Timeframe principal |
| `EMA_Rapida_Periodo` | 9 | EMA para sinais rápidos |
| `EMA_Lenta_Periodo` | 21 | EMA para tendência |
| `RSI_Periodo` | 14 | Período do RSI |
| `RSI_Sobrecompra` | 70 | Nível de sobrecompra |
| `RSI_Sobrevenda` | 30 | Nível de sobrevenda |

#### Seção: MACHINE LEARNING
| Parâmetro | Valor Padrão | Descrição |
|-----------|--------------|-----------|
| `Usar_ML_Padroes` | true | Ativar reconhecimento ML |
| `Limiar_Confianca_ML` | 0.7 | Confiança mínima (0-1) |
| `ML_Ajustar_StopLoss` | true | Ajuste dinâmico de SL |
| `Velas_Historico_ML` | 100 | Histórico para análise |

#### Seção: GESTÃO DE RISCO
| Parâmetro | Valor Padrão | Descrição |
|-----------|--------------|-----------|
| `Tipo_Gestao_Risco` | RISCO_PORCENTAGEM | Método de gestão |
| `Porcentagem_Risco` | 2.0 | % do capital por trade |
| `Usar_Trailing_Stop` | true | Ativar trailing stop |
| `Trailing_Stop_Pontos` | 50 | Distância em pontos |

#### Seção: CONTROLE DE OPERAÇÕES
| Parâmetro | Valor Padrão | Descrição |
|-----------|--------------|-----------|
| `Maximo_Trades_Dia` | 5 | Limite diário de trades |
| `Fechar_Trades_Sexta` | true | Fechar posições na sexta |
| `Horas_Fechar_Sexta` | 18 | Horário limite |
| `Permitir_Hedge` | false | Permitir posições opostas |

### Configurações por Ativo

#### Para EURUSD (Recomendado Inicial)
```ini
Timeframe: H1
Tamanho_Lote: 0.1
Trailing_Stop_Pontos: 30
ATR_Multiplier: 1.5
```

#### Para Pares Voláteis (GBPUSD, AUDUSD)
```ini
Timeframe: M15
Tamanho_Lote: 0.05
Trailing_Stop_Pontos: 50
ATR_Multiplier: 2.0
```

#### Para Ouro (XAUUSD)
```ini
Timeframe: H4
Tamanho_Lote: 0.01
Trailing_Stop_Pontos: 100
ATR_Multiplier: 2.5
```

---

## 📊 Estratégias de Trading

### Estratégia 1: Price Action Tradicional

**Descrição**: Baseada em padrões clássicos de candlestick com confirmação de indicadores.

**Regras de Entrada:**
```mql5
CONDIÇÃO_COMPRA = 
    PadrãoBullishDetectado() AND
    Preço > EMA_Rapida AND
    EMA_Rapida > EMA_Lenta AND
    RSI > 50 AND RSI < 70

CONDIÇÃO_VENDA = 
    PadrãoBearishDetectado() AND
    Preço < EMA_Rapida AND
    EMA_Rapida < EMA_Lenta AND
    RSI < 50 AND RSI > 30
```

**Padrões Detectados:**
1. **Engulfing de Alta/Baixa**
2. **Hammer/Shooting Star**
3. **Doji**
4. **Pin Bar**
5. **Morning/Evening Star**
6. **Three White Soldiers/Black Crows**

### Estratégia 2: Machine Learning

**Descrição**: Uso de algoritmos de ML para identificar padrões complexos.

**Features Analisadas:**
- Posição relativa no range
- Tamanho do corpo vs range
- Volume relativo
- Sequências de candles
- Correlações temporais
- Gaps entre aparições

**Score de Confiança:**
```mql5
SCORE_FINAL = 
    (Frequência * 0.4) +
    (Padrão * 0.3) +
    (Tendência * 0.2) +
    (Volume * 0.1)
```

**Limiar de Ação:**
- Score ≥ 0.7: Entrar no trade
- Score 0.5-0.7: Aguardar confirmação
- Score < 0.5: Ignorar sinal

### Estratégia 3: Híbrida (Recomendada)

**Descrição**: Combinação das duas estratégias anteriores.

**Vantagens:**
- Redução de falsos positivos
- Confirmação múltipla
- Adaptação ao mercado
- Maior robustez

**Fluxo de Decisão:**
```
Análise Price Action → Detecção Padrão → Score ML → Decisão Final
```

---

## 🧠 Machine Learning Detalhado

### Arquitetura do Sistema

#### 1. Extração de Features
```mql5
struct Features {
    double preco_normalizado[5];     // OHLC + média
    double volume_relativo;          // Volume vs média
    double tamanho_corpo;            // Corpo vs range
    double posicao_range;            // Posição no candle
    double sequencias[3];            // Sequências detectadas
    double gaps_temporais[5];        // Gaps históricos
    double correlacoes[10];          // Correlações entre números
};
```

#### 2. Algoritmos Implementados

**ML Equilibrado:**
```mql5
double calcularScoreEquilibrado(Features f) {
    return (f.tamanho_corpo * 0.3) + 
           (f.posicao_range * 0.3) + 
           (f.sequencias[0] * 0.2) + 
           (f.correlacoes[0] * 0.2);
}
```

**ML Frequência:**
```mql5
double calcularScoreFrequencia(Features f) {
    // Análise de frequência histórica
    double freq_score = analisarFrequencia(f);
    double gap_score = analisarGaps(f);
    return (freq_score * 0.6) + (gap_score * 0.4);
}
```

**ML Neural (Simulado):**
```mql5
double calcularScoreNeural(Features f) {
    // Simulação de rede neural
    double layer1 = tanh(dot_product(f.weights1, f.values));
    double layer2 = tanh(dot_product(f.weights2, layer1));
    return sigmoid(layer2);
}
```

#### 3. Treinamento do Modelo

**Coleta de Dados:**
```mql5
void coletarDadosTreinamento() {
    for(int i = 0; i < Periodo_Backtest_ML; i++) {
        Features f = extrairFeatures(i);
        double label = calcularLabel(i); // 1: Compra, -1: Venda, 0: Neutro
        adicionarAmostra(f, label);
    }
}
```

**Processo de Treinamento:**
1. Coletar dados históricos
2. Extrair features
3. Rotular resultados
4. Ajustar pesos
5. Validar modelo

#### 4. Integração ONNX (Futuro)

Para modelos ML mais avançados:

```mql5
#include <ONNX.mqh>

// Carregar modelo pré-treinado
bool carregarModeloONNX(string caminho) {
    CObject* modelo = new CObject();
    if(ModelLoad(caminho, modelo)) {
        Print("Modelo ONNX carregado com sucesso!");
        return true;
    }
    return false;
}

// Fazer previsão
double preverComONNX(Features f) {
    double input[] = {f.valores};
    double output[];
    ModelPredict(modelo, input, output);
    return output[0];
}
```

---

## 🛡️ Gestão de Risco Avançada

### Sistema Multi-Camadas

#### Camada 1: Prevenção
```mql5
bool validarPreCondicoes() {
    // 1. Limite diário de trades
    if(tradesHoje >= Maximo_Trades_Dia) return false;
    
    // 2. Distância mínima entre trades
    if(TimeCurrent() - ultimoTradeTime < Distancia_Minima_Entre_Trades*60) 
        return false;
    
    // 3. Filtro de notícias
    if(eventoNoticiaAtivo && Filtrar_Noticias) return false;
    
    // 4. Horário de trading
    if(!estaNoHorarioTrading()) return false;
    
    return true;
}
```

#### Camada 2: Proteção por Trade
```mql5
void calcularStopLossTakeProfit() {
    double atrAtual = atr.Main(0);
    double ponto = SymbolInfoDouble(_Symbol, SYMBOL_POINT);
    
    if(direcao == 1) { // COMPRA
        sl = precoAtual - (atrAtual * Multiplicador_ATR_SL);
        tp = precoAtual + (atrAtual * Multiplicador_ATR_TP);
    } else { // VENDA
        sl = precoAtual + (atrAtual * Multiplicador_ATR_SL);
        tp = precoAtual - (atrAtual * Multiplicador_ATR_TP);
    }
    
    // Ajuste baseado em confiança ML
    if(Usar_ML_Padroes && ML_Ajustar_StopLoss) {
        double ajuste = 1.0 - (confiancaML * 0.3); // Até 30% de ajuste
        if(direcao == 1) sl = precoAtual - ((atrAtual * Multiplicador_ATR_SL) * ajuste);
        else sl = precoAtual + ((atrAtual * Multiplicador_ATR_SL) * ajuste);
    }
}
```

#### Camada 3: Proteção da Conta
```mql5
void monitorarDrawdown() {
    double saldo = AccountInfoDouble(ACCOUNT_BALANCE);
    double equity = AccountInfoDouble(ACCOUNT_EQUITY);
    double drawdownPercent = ((saldo - equity) / saldo) * 100;
    
    // Níveis de alerta
    if(drawdownPercent > 10) {
        Print("ALERTA: Drawdown atingiu ", drawdownPercent, "%");
    }
    
    if(drawdownPercent > 20) {
        Print("PERIGO: Drawdown crítico de ", drawdownPercent, "%");
        // Tomar ações corretivas
        reduzirExposicao();
    }
    
    if(drawdownPercent > 30) {
        Print("EMERGÊNCIA: Drawdown extremo!");
        fecharTodasPosicoes();
        desativarEA();
    }
}
```

#### Camada 4: Trailing Stop Inteligente
```mql5
void aplicarTrailingStop() {
    if(!Usar_Trailing_Stop || !PositionSelect(_Symbol)) return;
    
    long tipo = PositionGetInteger(POSITION_TYPE);
    double precoAtual = PositionGetDouble(POSITION_PRICE_CURRENT);
    double slAtual = PositionGetDouble(POSITION_SL);
    double ponto = SymbolInfoDouble(_Symbol, SYMBOL_POINT);
    
    if(tipo == POSITION_TYPE_BUY) {
        double novoSL = precoAtual - (Trailing_Stop_Pontos * ponto);
        // Só move se for favorável e maior que SL atual
        if(novoSL > slAtual && novoSL > precoEntrada) {
            trade.PositionModify(_Symbol, novoSL, PositionGetDouble(POSITION_TP));
        }
    } else if(tipo == POSITION_TYPE_SELL) {
        double novoSL = precoAtual + (Trailing_Stop_Pontos * ponto);
        if((novoSL < slAtual || slAtual == 0) && novoSL < precoEntrada) {
            trade.PositionModify(_Symbol, novoSL, PositionGetDouble(POSITION_TP));
        }
    }
}
```

### Cálculo de Tamanho de Lote

```mql5
double calcularTamanhoLote() {
    double saldo = AccountInfoDouble(ACCOUNT_BALANCE);
    double loteCalculado = Tamanho_Lote;
    
    switch(Tipo_Gestao_Risco) {
        case RISCO_PORCENTAGEM:
            // Exemplo: 2% de risco com saldo de 10.000 = risco de 200
            // Se SL é 100 pontos e valor por ponto é 10, lote = 200 / (100 * 10) = 0.2
            double riscoReais = saldo * (Porcentagem_Risco / 100);
            double distanciaSL = calcularDistanciaSL(); // em pontos
            double valorPorPonto = SymbolInfoDouble(_Symbol, SYMBOL_TRADE_TICK_VALUE);
            loteCalculado = riscoReais / (distanciaSL * valorPorPonto);
            break;
            
        case RISCO_FIXO:
            // Risco fixo em reais/dólares
            loteCalculado = Risco_Fixo_Por_Trade / 1000;
            break;
            
        case RISCO_ATR:
            // Baseado na volatilidade (ATR)
            double atrAtual = atr.Main(0);
            double valorPonto = SymbolInfoDouble(_Symbol, SYMBOL_TRADE_TICK_VALUE);
            loteCalculado = (saldo * 0.01) / (atrAtual * valorPonto);
            break;
    }
    
    // Ajustar para limites do símbolo
    double loteMin = SymbolInfoDouble(_Symbol, SYMBOL_VOLUME_MIN);
    double loteMax = SymbolInfoDouble(_Symbol, SYMBOL_VOLUME_MAX);
    double loteStep = SymbolInfoDouble(_Symbol, SYMBOL_VOLUME_STEP);
    
    loteCalculado = MathMax(loteMin, MathMin(loteCalculado, loteMax));
    loteCalculado = MathRound(loteCalculado / loteStep) * loteStep;
    
    return NormalizeDouble(loteCalculado, 2);
}
```

---

## 📰 Análise Fundamental Integrada

### Sistema de Filtro de Notícias

```mql5
void verificarEventosFundamentais() {
    datetime agora = TimeCurrent();
    MqlDateTime dt;
    TimeToStruct(agora, dt);
    
    // Reinicializar status
    eventoNoticiaAtivo = false;
    ultimoEventoEconomico = "";
    
    // Eventos de Alto Impacto (Exemplos)
    
    // 1. Non-Farm Payrolls (EUA) - Primeira sexta do mês, 8:30 EST
    if(dt.day_of_week == 5 && dt.day <= 7) {
        if((dt.hour == 8 && dt.min >= 30) || (dt.hour == 9 && dt.min <= 30)) {
            eventoNoticiaAtivo = true;
            ultimoEventoEconomico = "Non-Farm Payrolls (EUA)";
        }
    }
    
    // 2. Taxa de Juros FED - Datas pré-agendadas
    if(ehDataReuniaoFED(agora)) {
        eventoNoticiaAtivo = true;
        ultimoEventoEconomico = "Decisão de Juros FED";
    }
    
    // 3. CPI (Inflação EUA) - Geralmente dia 13-15 do mês
    if((dt.day >= 13 && dt.day <= 15) && dt.hour == 8 && dt.min >= 30) {
        eventoNoticiaAtivo = true;
        ultimoEventoEconomico = "CPI (Inflação EUA)";
    }
    
    // Log se evento detectado
    if(eventoNoticiaAtivo && Log_Detalhado) {
        Print("EVENTO ECONÔMICO ATIVO: ", ultimoEventoEconomico);
        Print("Trading pausado até: ", TimeToString(agora + Minutos_Apos_Noticia*60));
    }
}
```

### Lista de Eventos Monitorados

#### Alto Impacto (Trading Pausado)
1. **Non-Farm Payrolls** (EUA)
2. **Decisões de Taxa de Juros** (FED, BCE, BoE, BoJ)
3. **CPI/Inflação** (EUA, Zona Euro)
4. **GDP/PIB** Trimestral
5. **Reuniões do FOMC**

#### Médio Impacto (Redução de Exposição)
1. **Retail Sales** (Varejo)
2. **PMI/ISM Manufacturing**
3. **Unemployment Rate** (Taxa Desemprego)
4. **Housing Data** (Dados Imobiliários)

#### Implementação Prática
```mql5
bool podeOperarDuranteNoticia() {
    if(!Filtrar_Noticias) return true;
    
    if(eventoNoticiaAtivo) {
        // Verificar nível de impacto
        if(Impacto_Minimo_Noticias >= 2) { // Alto impacto
            return false;
        } else if(Impacto_Minimo_Noticias == 1) { // Médio impacto
            // Reduzir tamanho do lote
            Tamanho_Lote *= 0.5;
            return true;
        }
    }
    return true;
}
```

---

## 📈 Backtesting Completo

### Configuração Recomendada para Testes

#### Configurações do Strategy Tester
```ini
[Geral]
Símbolo: EURUSD
Período: H1
Modelo: Cada tick (mais preciso)
Data Início: 2020-01-01
Data Fim: 2024-12-31
Depósito Inicial: 10000
Moeda da Conta: USD
Alavancagem: 1:100

[EA]
Tamanho_Lote: 0.1
Porcentagem_Risco: 2.0
Usar_ML_Padroes: true
Filtrar_Noticias: true

[Otimização]
Método: Algoritmo Genético
Critério de Otimização: Profit Factor
Número de Passos: 50000
```

### Métricas de Avaliação

#### 1. Profit Factor
```mql5
// Ideal: > 1.5
// Bom: 1.2 - 1.5
// Aceitável: 1.0 - 1.2
// Ruim: < 1.0
```

#### 2. Win Rate (Taxa de Acerto)
```mql5
// Excelente: > 60%
// Bom: 55% - 60%
// Aceitável: 50% - 55%
// Melhorar: < 50%
```

#### 3. Maximum Drawdown (MDD)
```mql5
// Conservador: < 10%
// Moderado: 10% - 20%
// Agressivo: 20% - 30%
// Perigoso: > 30%
```

#### 4. Sharpe Ratio
```mql5
// Excelente: > 1.5
// Bom: 1.0 - 1.5
// Aceitável: 0.5 - 1.0
// Ruim: < 0.5
```

#### 5. Recovery Factor
```mql5
// Excelente: > 3.0
// Bom: 2.0 - 3.0
// Aceitável: 1.0 - 2.0
// Ruim: < 1.0
```

### Script de Análise Automática
```mql5
// AnalisadorBacktest.mq5
void analisarResultados() {
    // Coletar métricas
    double profitFactor = TesterStatistics(STAT_PROFIT_FACTOR);
    double winRate = (TesterStatistics(STAT_PROFIT_TRADES) / 
                     TesterStatistics(STAT_TRADES)) * 100;
    double mdd = TesterStatistics(STAT_MAX_DRAWDOWN);
    double sharpe = calcularSharpeRatio();
    
    // Gerar relatório
    string relatorio = "===== RELATÓRIO BACKTEST =====\n";
    relatorio += StringFormat("Profit Factor: %.2f\n", profitFactor);
    relatorio += StringFormat("Win Rate: %.1f%%\n", winRate);
    relatorio += StringFormat("Max Drawdown: %.2f%%\n", mdd);
    relatorio += StringFormat("Sharpe Ratio: %.2f\n", sharpe);
    
    // Avaliação
    if(profitFactor > 1.5 && winRate > 55 && mdd < 20) {
        relatorio += "\n✅ ESTRATÉGIA APROVADA\n";
    } else {
        relatorio += "\n⚠️ ESTRATÉGIA NECESSITA AJUSTES\n";
    }
    
    Print(relatorio);
    FileWrite("relatorio_backtest.txt", relatorio);
}
```

---

## ⚙️ Otimização Avançada

### Parâmetros para Otimização

```mql5
// Arquivo: JarvesTrader_Optimize.mq5

// Grupo: Indicadores Técnicos
input int EMA_Fast_Optimize = 9;        // Min:5, Max:15, Step:2
input int EMA_Slow_Optimize = 21;       // Min:15, Max:30, Step:3
input int EMA_Trend_Optimize = 50;      // Min:30, Max:100, Step:10

// Grupo: RSI
input int RSI_Period_Optimize = 14;     // Min:10, Max:20, Step:2
input double RSI_Overbought_Optimize = 70; // Min:65, Max:75, Step:2.5
input double RSI_Oversold_Optimize = 30;   // Min:25, Max:35, Step:2.5

// Grupo: ATR e Stops
input double ATR_Multiplier_SL_Optimize = 1.5; // Min:1.0, Max:3.0, Step:0.25
input double ATR_Multiplier_TP_Optimize = 2.0; // Min:1.5, Max:3.5, Step:0.25

// Grupo: ML
input double ML_Confidence_Threshold_Optimize = 0.7; // Min:0.5, Max:0.9, Step:0.05
```

### Métodos de Otimização

#### 1. Algoritmo Genético (Recomendado)
```ini
População Inicial: 100
Número de Gerações: 50
Taxa de Mutação: 0.1
Critério de Parada: 5 gerações sem melhoria
```

#### 2. Walk-Forward Analysis
```mql5
// Divisão do período
Periodo Otimização: 70% dos dados
Periodo Teste: 30% dos dados
Janela Deslizante: 3 meses
```

#### 3. Monte Carlo Simulation
```mql5
void simularMonteCarlo() {
    int simulacoes = 1000;
    for(int i = 0; i < simulacoes; i++) {
        // Aleatorizar ordem dos trades
        // Calcular drawdown máximo
        // Verificar probabilidade de ruína
    }
}
```

### Critérios de Otimização

```mql5
// Prioridade 1: Minimizar Drawdown
double criterio1 = 100 - TesterStatistics(STAT_MAX_DRAWDOWN);

// Prioridade 2: Maximizar Profit Factor
double criterio2 = TesterStatistics(STAT_PROFIT_FACTOR) * 50;

// Prioridade 3: Maximizar Win Rate
double criterio3 = (TesterStatistics(STAT_PROFIT_TRADES) / 
                   TesterStatistics(STAT_TRADES)) * 100;

// Cálculo Final
double criterioFinal = (criterio1 * 0.4) + 
                      (criterio2 * 0.4) + 
                      (criterio3 * 0.2);
```

### Validação Cruzada

```mql5
void validacaoCruzada() {
    // Dividir dados em k folds
    int k = 5;
    for(int fold = 0; fold < k; fold++) {
        // Treinar com k-1 folds
        // Testar com 1 fold
        // Calcular métricas
    }
    
    // Média das métricas
    double mediaProfitFactor = calcularMedia(folds, "profitFactor");
    double mediaWinRate = calcularMedia(folds, "winRate");
    
    // Consistência entre folds
    if(desvioPadrao(mediaProfitFactor) < 0.2 && 
       desvioPadrao(mediaWinRate) < 5) {
        Print("✅ Modelo consistente na validação cruzada");
    }
}
```

---

## ❓ FAQ - Perguntas Frequentes

### 1. Quanto tempo devo testar em DEMO antes de usar real?
**Resposta:** Mínimo de 30 dias ou 100 trades, o que ocorrer primeiro. Idealmente 3 meses para ver diferentes condições de mercado.

### 2. Posso usar o EA em múltiplos pares simultaneamente?
**Sim.** Cada instância é independente. Recomendamos começar com 1-2 pares e expandir gradualmente.

### 3. Qual é o drawdown máximo esperado?
O sistema é configurado para manter drawdown abaixo de 20%. Em backtesting, geralmente fica entre 10-15%.

### 4. Preciso de VPS?
Para operação 24/7, sim. Para trading manual durante o dia, pode usar seu computador.

### 5. Como atualizar para novas versões?
1. Desative o EA atual
2. Baixe a nova versão
3. Substitua os arquivos
4. Recompile
5. Reative no gráfico

### 6. O EA funciona em smartphones?
Não diretamente. MetaTrader 5 mobile não suporta EAs. Precisa de MT5 desktop ou VPS.

### 7. Posso modificar o código?
Sim! O código é open-source. Modifique conforme necessário, mas teste cada alteração.

### 8. Há garantia de lucro?
**Absolutamente não.** Trading envolve riscos. O EA é uma ferramenta, não uma garantia.

### 9. Qual broker recomenda?
Qualquer broker confiável com MT5 e spreads baixos. Teste com seu broker atual em DEMO primeiro.

### 10. Onde vejo os logs?
No MT5: Menu "Exibir" → "Expert Advisors" → Abra a aba "Experts" (Ctrl+T).

---

## 📞 Suporte e Contato

### Canais de Suporte

#### 1. WhatsApp (Prioritário)
**Número:** [(99) 9 8444-7141](https://wa.me/5599984447141)
- Resposta em até 2 horas úteis
- Suporte técnico gratuito
- Ajuda com configuração
- Solução de problemas

#### 2. Email
**Endereço:** [natal.santiago.tech@gmail.com](mailto:natal.santiago.tech@gmail.com)
- Para questões detalhadas
- Relatórios de bugs
- Sugestões de features
- Parcerias

#### 3. GitHub Issues
Para problemas técnicos e feature requests.

### Horário de Atendimento
- **Segunda a Sexta:** 9:00 às 18:00 (BRT)
- **Sábado:** 10:00 às 14:00 (BRT)
- **Domingo:** Plantão apenas para emergências

### Tipos de Suporte Oferecidos

#### Gratuito (Incluído)
✅ Instalação básica  
✅ Configuração inicial  
✅ Dúvidas sobre parâmetros  
✅ Solução de erros comuns  

#### Premium (Consultoria Paga)
🔧 Otimização personalizada  
🎯 Estratégias customizadas  
📊 Análise de resultados  
🚀 Configuração VPS  
🤝 Mentoria de trading  

---

## 🤝 Contribuição

### Como Contribuir

1. **Fork o repositório**
2. **Crie uma branch**
```bash
git checkout -b feature/nova-funcionalidade
```
3. **Faça suas alterações**
4. **Commit**
```bash
git commit -m "feat: Adiciona funcionalidade X"
```
5. **Push**
```bash
git push origin feature/nova-funcionalidade
```
6. **Abra um Pull Request**

### Áreas que Precisam de Contribuição

1. **Novos Padrões de Candlestick**
2. **Indicadores Técnicos Adicionais**
3. **Traduções para Outros Idiomas**
4. **Testes em Diferentes Ativos**
5. **Documentação e Tutoriais**

### Diretrizes para Contribuidores

- Mantenha o código comentado em português
- Siga o estilo de código existente
- Teste suas alterações antes de submeter
- Atualize a documentação se necessário
- Use commits semânticos

---

## 📄 Licença

### MIT License

```
Copyright (c) 2024 SantiagoTECH

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
```

### Permissões
✅ Uso Comercial  
✅ Modificação  
✅ Distribuição  
✅ Uso Privado  

### Condições
⚠️ Incluir aviso de copyright e licença  
⚠️ Não há garantia  
⚠️ Responsabilidade limitada  

---

## 💖 Apoio ao Projeto

### Por que Apoiar?

Este projeto é desenvolvido gratuitamente para a comunidade brasileira de traders. Seu apoio ajuda:

1. **Manter o desenvolvimento ativo**
2. **Adicionar novas funcionalidades**
3. **Oferecer suporte gratuito**
4. **Criar mais conteúdo educativo**
5. **Melhorar a estabilidade do sistema**

### Como Apoiar

#### 1. Doação via PIX (Recomendado)
**Chave PIX:** `523.741.143-68`  
**Nome:** Natal de Jesus da Silva Santiago  
**Valor:** Qualquer valor é bem-vindo!

<div align="center">

### 💰 Doação via PIX

**CPF:** 523.741.143-68

![Captura de Tela](qrcode_pix.png)

*Escaneie o QR Code acima ou use a chave PIX: 523.741.143-68*

---

**Sua contribuição ajuda a manter este projeto ativo e em constante evolução!**

</div>

#### 3. Outras Formas de Apoio
- ⭐ **Dê uma estrela no GitHub**
- 📢 **Compartilhe com outros traders**
- 🐛 **Reporte bugs e sugira melhorias**
- 💬 **Participe da comunidade**
- 📝 **Contribua com código ou documentação**

### Recompensas para Apoiadores

#### Apoio Único (Qualquer valor)
✅ Agradecimento no README  
✅ Acesso antecipado a novas versões  
✅ Suporte prioritário por 30 dias  

#### Apoio Mensal (R$ 50+)
✅ Todas as recompensas anteriores  
✅ Configuração personalizada  
✅ Consultoria mensal  
✅ Acesso a estratégias exclusivas  

### Transparência

Todo valor recebido é reinvestido no projeto:
- 50%: Desenvolvimento de novas features
- 30%: Infraestrutura (VPS, domínio, etc.)
- 20%: Conteúdo educativo e suporte

---

## 🎉 Agradecimentos

### Apoiadores Especiais
*(Lista será atualizada com contribuições)*

### Recursos Utilizados
- **MetaQuotes** pela plataforma MetaTrader 5
- **Comunidade MQL5** pela documentação e exemplos
- **GitHub** por hospedar o projeto
- **Stack Overflow** pelas soluções técnicas

### Inspiração
- Comunidade brasileira de traders
- Projetos open-source de trading
- Inovações em Machine Learning aplicado
- Educação financeira acessível

---

## 📊 Estatísticas do Projeto

### Métricas de Desenvolvimento
- **Linhas de Código:** 2,500+
- **Arquivos:** 15+
- **Horas de Desenvolvimento:** 300+
- **Testes Realizados:** 50+ configurações

### Comunidade
![GitHub stars](https://img.shields.io/github/stars/NatalSantiago/Jarves-Trader?style=social)
![GitHub forks](https://img.shields.io/github/forks/NatalSantiago/Jarves-Trader?style=social)
![GitHub watchers](https://img.shields.io/github/watchers/NatalSantiago/Jarves-Trader?style=social)

### Atividade
![GitHub issues](https://img.shields.io/github/issues/NatalSantiago/Jarves-Trader)
![GitHub pull requests](https://img.shields.io/github/issues-pr/NatalSantiago/Jarves-Trader)
![GitHub last commit](https://img.shields.io/github/last-commit/NatalSantiago/Jarves-Trader)

---

## 🔄 Histórico de Versões

### v2.0.0 (Atual)
- ✅ Machine Learning integrado
- ✅ 12 padrões de candlestick
- ✅ Gestão de risco multi-camadas
- ✅ Análise fundamental
- ✅ Interface em português

### v1.5.0
- ✅ Estratégia price action básica
- ✅ Indicadores técnicos
- ✅ Gestão de risco simples
- ✅ Backtesting funcional

### Próximas Versões
- 🚀 v2.1.0: Integração com APIs reais
- 🚀 v2.2.0: Painel web de monitoramento
- 🚀 v3.0.0: ML com TensorFlow.js

---

<div align="center">

## 🚀 Comece Agora!

**[⬇️ BAIXAR VERSÃO 2.0](https://github.com/NatalSantiago/Jarves-Trader/releases/latest)**

### Passos Rápidos:
1. **Baixe** o EA
2. **Instale** no MT5
3. **Teste** em DEMO
4. **Otimize** para seu estilo
5. **Monitore** os resultados

### 📞 Precisa de Ajuda?
**WhatsApp:** [(99) 9 8444-7141](https://wa.me/5599984447141)  
**Email:** [natal.santiago.tech@gmail.com](mailto:natal.santiago.tech@gmail.com)

---

⭐ **Se este projeto te ajudar, dê uma estrela no GitHub!**  
💖 **Apoie o desenvolvimento via PIX: 523.741.143-68**

**Desenvolvido com ❤️ por SantiagoTECH para a comunidade brasileira**

📈 **Trade com Sabedoria, Gerencie com Disciplina!**

[⬆ Voltar ao Topo](#-jarves-trader---expert-advisor-para-metatrader-5)

</div>
