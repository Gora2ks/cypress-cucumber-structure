Para instalar node_modules:
npm install --save-dev cypress-cucumber-preprocessor

Existe uma falha no plugin cucumber que n�o permite o uso de tags no windows. Para corrigir, siga o seguinte passo:

O arquivo "cypress-tags.js" deve ser colado no seguinte caminho (deve substituir o arquivo j� existente): 

C: \node_modules\cypress-cucumber-preprocessor