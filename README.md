# pipeline_poc


nvestigation Points:
| Check | Ing                                           | Port                                                  |
|-------|-----------------------------------------------|-------------------------------------------------------|
| [ X ] | Check publishing in different environments    | Verifique a publicação em diferentes ambientes        |
| [   ] | Check build steps                             | Verifique as etapas de construção                     |
| [   ] | Check release management                      | Verifique o gerenciamento de liberação                |
| [   ] | Check tagging process                         | Verifique o processo de marcação                      |
| [   ] | Check quality steps                           | Verifique as etapas de qualidade                      |
| [   ] | Check 3rd party integrations (Eg: Jira)       | Verifique integrações de terceiros (por exemplo: Jira)|
| [   ] | Check Nexus integration                       | Verifique a integração do Nexus                       |
| [   ] | Check checkstyle process                      | Verifique o processo de estilo de verificação         |
| [   ] | Check truststore validation process           | Verifique o processo de validação do truststore       |
| [   ] | Check vulnerability check                     | Verifique a verificação de vulnerabilidade            |
      

## Enviroments
* eu_dev
* eu_int
* eu_e2e
* us_e2e

## Documentação
[Doc tag-bump](https://github.com/marketplace/actions/github-tag-bump)
[Doc Release](https://github.com/marketplace/actions/automatic-releases)



* fazer nas features comitar com #patch ? ou talvez setar isso default sei lah
* fazer uma action para release para criar os minors

# DEFAULT_BUMP (optional) - Which type of bump to use when none explicitly provided (default: minor).

feature PR para develop => patch
release PR para develop => minor
develop PR para main    => major