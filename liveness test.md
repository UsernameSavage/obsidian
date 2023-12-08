       livenessProbe:  
         failureThreshold: 3  
         httpGet:  
           path: /actuator/health/liveness  
           port: 80  
           scheme: HTTP  
         initialDelaySeconds: 30  
         periodSeconds: 30  
         successThreshold: 1  
         timeoutSeconds: 10