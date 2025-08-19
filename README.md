# 📌 Proyecto: Análisis de Evasión de Clientes - Telecom X

## 📖 Descripción
Este proyecto tiene como objetivo analizar la **tasa de abandono de clientes (Churn)** en la empresa de telecomunicaciones *Telecom X*.  
Se busca identificar los factores que influyen en la cancelación de los servicios y proponer estrategias para mejorar la retención de clientes.

---

## ⚙️ Tecnologías utilizadas
- Python 🐍
- Pandas
- Matplotlib
- Seaborn
- Jupyter Notebook

---

## 📊 Análisis Exploratorio de Datos (EDA)

Se analizaron **7,043 registros de clientes**.  
Del análisis descriptivo se obtuvo:

- El **26.5% de los clientes abandonaron el servicio** (1,869 clientes).  
- El **73.5% permanecieron** (5,174 clientes).  

### Distribución de clientes


### Variables categóricas
- No existe diferencia significativa entre hombres y mujeres en la tasa de abandono.  
- Los contratos **mensuales** presentan mayor evasión frente a los contratos a largo plazo.  
- Los clientes que pagan con **cheque electrónico** son los que más abandonan.  
- Los usuarios con **fibra óptica** muestran mayor tasa de abandono frente a DSL.  



### Correlación entre variables numéricas
- **Antigüedad (meses_en_empresa)**: correlación negativa (-0.35) → a mayor tiempo en la empresa, menor probabilidad de abandonar.  
- **Cargos mensuales**: correlación positiva (0.19) → clientes con cargos altos tienden a abandonar.  
- **Factura electrónica**: ligera mayor tendencia a abandonar.  
- **Cargos totales**: correlación negativa (-0.19) → clientes con más gasto acumulado son más fieles.  
- **Clientes seniors**: leve mayor probabilidad de abandono (0.15).  



---

## ✅ Conclusiones
1. El **abandono es del 26.5%**, lo que representa un desafío importante.  
2. Los **clientes nuevos, con planes mensuales y con cargos altos** son los más propensos a dejar el servicio.  
3. Los **clientes de alto valor (más gasto acumulado)** presentan mayor fidelidad.  
4. Los clientes que pagan con **cheque electrónico** y los que usan **fibra óptica** presentan mayor tasa de abandono.  
5. Los **clientes seniors** necesitan una atención diferenciada, ya que presentan mayor riesgo de churn.  

---

## 🚀 Recomendaciones
1. **Fomentar contratos de largo plazo** (anuales o semestrales) con descuentos y beneficios.  
2. **Revisar la política de precios**: planes escalonados y programas de fidelización para clientes con cargos altos.  
3. **Mejorar la experiencia digital**: optimizar la factura electrónica y fortalecer el soporte en línea.  
4. **Atención diferenciada a clientes seniors**: soporte personalizado y programas de capacitación tecnológica.  
5. **Reducir dependencia de métodos de pago riesgosos** (cheque electrónico), promoviendo pagos automáticos o digitales.  
6. **Onboarding de clientes nuevos**: beneficios exclusivos y acompañamiento en los primeros meses para aumentar la retención.  

---

## ✨ Autor
**Alberto Gonzales**  
Proyecto Challenge Data Science de Alura📊 
