# Customer-churn-model

This case study consists of calculating the churn of customers in a telecommunications company.
The company has found that between December 2019 and January 2020 they have had quite a few customer casualties.
The objective is to build an analytical model that is capable of predicting the next customers who are potential to leave the operator in order to launch a campaign and try to retain them before portability.
In addition, company managers want to know the reasons why customers are leaving.
For this I worked with six datasets with data that provide customer information.

### Dataset information

#### Dataset CLIENTES
- edad: age of customers.
- facturacion: money paid by customers per month.
- antiguedad: date of customer registration.
- provincia: customer city.
- num_lineas: number of mobile lines contracted.
- num_dt: number of lines in default.
- incidencia: it is 'SI', if the client has had any incident.

#### Dataset PRODUCTOS
- conexión: customer's internet connection type.
- vel_conexion: internet connection speed.
- TV: type of tv package contracted by the client.
 
#### Dataset CONSUMOS
- num_llamad_ent: number of calls received from all your lines.
- num_llamad_sal: number of calls made from all your lines.
- mb_datos: mb of data consumed on all its lines.
- seg_llamad_ent: seconds spent on received calls.
- seg_llamad_sal: seconds spent on calls made.

#### Dataset FINANCIACION
- financiación: it is 'SI', if the client has any financing
- imp_financ: the monthly money you pay for the financed lines.
- descuentos: it is 'SI', if the client has an active discount (campaign).

