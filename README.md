## twitter005 | #つぶやきProcessing 
https://twitter.com/nicolasbaez/status/1248852956168040448?s=20

![twitter](https://github.com/nicolasbaez/twitter005/blob/master/twitter005-001650.png)
```processing
float r[]=new float [9];float h,t,i,j;void setup(){size(512,256);h=256;}void draw(){beginShape();int p=0;noFill();stroke(random(255),0,0);for(i=0;i<540;i+=60){t=r[p];curveVertex(t*cos(radians(i))+h,t*sin(radians(i))+128);r[p]+=random(-1,1.4);p++;}endShape();}
```
