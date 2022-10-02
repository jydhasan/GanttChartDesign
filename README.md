
# Gantt Cahrt design

Gant chart is  very useful to the project manager for their project management

## Deployment

To deploy this project run

```bash
  Sign mark at the end  =IF(($F6=M$4),"U","")
  Graph design bar fron start to end =AND(K$4>=$E6-(WEEKDAY($E6,2)+1),K$4<=$F6)
  Graph for the persentage of project design and cover
  =AND($I6>0,K$4<=($E6+($F6-$E6)*$I6)-WEEKDAY(($E6+($F6-$E6)*$I6),2)+1,K$4>=$E6-WEEKDAY($E6,2)+1)
```



## Demo

![photo](https://github.com/jydhasan/GanttChartDesign/blob/main/EXCEL_wUU9jW6sP4.png)

