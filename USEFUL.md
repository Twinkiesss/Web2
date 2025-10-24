ssh -p 2222 s408931@se.ifmo.ru -L 34318:helios.cs.ifmo.ru:34318
bash wildfly-21.0.0.Final/bin/standalone.sh
http://localhost:34318/web2

cd web/lab2/wildfly-21.0.0.Final/standalone/deployments



bash wildfly-21.0.0.Final/bin/standalone.sh