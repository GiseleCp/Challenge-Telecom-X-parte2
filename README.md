<h1 align="center">📊 Projeto de Previsão de Evasão de Clientes</h1>

<p align="center">
  <strong>Modelagem preditiva aplicada à base TelecomX</strong><br>
  <em>Com uso de Machine Learning e análise estratégica para retenção de clientes</em>
</p>

---

<h2>📌 Objetivo</h2>

<p>
Antecipar a evasão de clientes (churn) com modelos de machine learning aplicados a dados reais da TelecomX. O objetivo é entender os principais fatores que contribuem para a saída dos clientes e propor estratégias eficazes de retenção.
</p>

---

<h2>🧠 Etapas Realizadas</h2>

<ul>
  <li>✔️ Importação e inspeção inicial dos dados</li>
  <li>✔️ Tratamento e codificação de variáveis (One-Hot Encoding)</li>
  <li>✔️ Balanceamento de classes com SMOTE</li>
  <li>✔️ Normalização e padronização (quando necessário)</li>
  <li>✔️ Análise de correlação com a variável alvo (<code>contrato.ativo</code>)</li>
  <li>✔️ Visualização de relações entre variáveis e evasão (boxplots, scatterplots)</li>
  <li>✔️ Separação em treino e teste (70/30)</li>
  <li>✔️ Treinamento e avaliação de múltiplos modelos:</li>
    <ul>
      <li>Regressão Logística</li>
      <li>Random Forest</li>
      <li>SVM Linear</li>
      <li>KNN</li>
      <li>XGBoost</li>
    </ul>
  <li>✔️ Análise da importância das variáveis por modelo</li>
  <li>✔️ Geração de gráfico comparativo das variáveis mais influentes</li>
  <li>✔️ Conclusão estratégica com recomendações práticas</li>
</ul>

---

<h2>📈 Avaliação dos Modelos</h2>

<table>
  <thead>
    <tr>
      <th>Modelo</th>
      <th>Acurácia</th>
      <th>Precisão</th>
      <th>Recall</th>
      <th>F1-Score</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Regressão Logística</td>
      <td>79.84%</td>
      <td>64.15%</td>
      <td>54.55%</td>
      <td>58.96%</td>
    </tr>
    <tr>
      <td>Random Forest</td>
      <td>78.75%</td>
      <td>62.73%</td>
      <td>49.20%</td>
      <td>55.14%</td>
    </tr>
    <tr>
      <td>SVM (Linear)</td>
      <td>79.18%</td>
      <td>62.42%</td>
      <td>54.19%</td>
      <td>58.02%</td>
    </tr>
    <tr>
      <td>XGBoost</td>
      <td>78.28%</td>
      <td>60.71%</td>
      <td>51.52%</td>
      <td>55.74%</td>
    </tr>
    <tr>
      <td>KNN</td>
      <td>74.35%</td>
      <td>51.76%</td>
      <td>49.91%</td>
      <td>50.82%</td>
    </tr>
  </tbody>
</table>

---

<h2>🔍 Principais Variáveis Identificadas</h2>

<ul>
  <li><strong>cliente.tempo.contrato</strong></li>
  <li><strong>internet.assinatura_fiber optic</strong></li>
  <li><strong>internet.assinatura_no</strong></li>
  <li><strong>conta.tipo.contrato_two year</strong></li>
  <li><strong>conta.valor.total.acumulado</strong></li>
  <li><strong>conta.metodo.pagamento_electronic check</strong></li>
</ul>

---

<h2>💡 Estratégias de Retenção Sugeridas</h2>

<ul>
  <li>🕵️‍♂️ Monitorar clientes com <strong>contrato recente</strong> e plano <strong>fiber optic</strong></li>
  <li>💰 Clientes com <strong>gastos altos acumulados</strong> devem receber atenção especial</li>
  <li>🔁 Estimular o uso de <strong>pagamentos automáticos</strong> em vez de “electronic check”</li>
  <li>🎁 Oferecer serviços adicionais que aumentem o valor percebido (streaming, suporte técnico)</li>
</ul>

---

<h2>📁 Estrutura do Projeto</h2>

📂 projeto-churn-telecomx/
├── data/
│ └── TelecomX_normalizado.json2
├── notebooks/
│ └── churn_modeling.ipynb
├── README.md
└── requirements.txt



---

<h2>👩‍💻 Tecnologias Utilizadas</h2>

<ul>
  <li>Python 3</li>
  <li>Pandas, NumPy</li>
  <li>Scikit-learn</li>
  <li>XGBoost</li>
  <li>Matplotlib, Seaborn</li>
</ul>

---

<h2>🚀 Resultado</h2>

<p>
Projeto entregue com sucesso, gerando insights estratégicos para a tomada de decisão na área de Customer Success e Marketing da empresa TelecomX.
</p>

<p align="center"><strong>Missão Concluída ✅</strong></p>


