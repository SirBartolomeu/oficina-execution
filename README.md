# oficina-execution

Catálogo, estoque e execução de reparos.

Este repositório foi extraído do histórico Git do projeto `oficina-mvp`.
Commit de origem: ea5a8df43e449555a11df0253ef1d1aa6c749937.

```powershell
dotnet test services/Oficina.Execution.Tests --configuration Release
```

O workflow em `.github/workflows` executa testes, publica a imagem no ECR por OIDC e aciona o deploy K3s por SSM quando as variáveis GitHub estiverem configuradas.
