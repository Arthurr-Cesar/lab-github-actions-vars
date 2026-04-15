#Por que a Secret aparece no log como *** e a variavel aparece normalmente?
R: O Github esconde automaticamente valores do tipo secret nos logs

# O Job 2 consegue ler a variavel BUILD_VERSION criada no Job 1? Por que?
R: Não, cada job possui seu ambiente isolado, de forma com que variáveis não
são compartilhadas automaticamente
