## Основная идея

* Есть несколько текущих и потенциальных проектов
* Типовой проект выглядит следующим образом
    * Команды: Developers (BE/FE/DBA/..., ~10+ человек), QA, PM, Marketing/SEO, ...
    * Разрабатываемое приложение развернутое в промышеленной среде (реальные пользователи, которые за что-то платят)
    * Инфраструктура используемая для промышленной среды
    * Инфраструктура используемая для какого-то количества непромышленных сред, таких как, например, тестовая
* Требуется команда способная решать следующиее типовые задачи для данных проектов
    * сопровождение и развитие инфраструктуры
    * поддержка жизненного цикла разработки
    * повышение доступности, обеспеченине надежности, мониторинг
* Есть идея найти и обучить студентов

## Требования

* Студенты инженерных специальностей, которым было бы интересно развиваться в направлении связанном с решенинем подобных задач
    * Возможно, на начальном этапе, потенциалные специалист еще не знакомы с таким направлением и имеет смысл ориентироваться на развитие следующих навыков 
        * Linux System Administration: Networking, Containerization, Shell Scripting, OS Troubleshooting
* Основные требования
    * Понимание (на данный момент или в процессе обучения), что это данное направление им интересно и есть готованость погружаться в указанные технологии
    * Способность читать и воспринимать сложные технические тексты на английском (документация провайдеров, руководства Linux/Unix (man)

## Детали 

* Используемая инфраструктура
    * Облачные сервисы
        * [Amazon AWS](https://skillbuilder.aws/getstarted)
        * [Google GCP](https://www.freecodecamp.org/news/google-cloud-platform-from-zero-to-hero/)
    * Системы контейнеризации и оркестрации контейнеров
        * [Kubernetes](https://kubernetes.io/training/)
        * [Docker](https://docs.docker.com/get-started/resources/)
* Платформы управления жизненным циклом разработки
    * [GitHub Actions](https://docs.github.com/en/actions/quickstart)
    * [GitLab pipelines](https://docs.gitlab.com/ee/ci/quick_start/)
* Инструменты автоматизации управления инфраструктурой и развертывания приложенний
    * [terraform](https://developer.hashicorp.com/terraform/tutorials)
    * [helm](https://helm.sh/docs/intro/quickstart/)
    * [helmfile](https://gitlab.com/gitlab-com/gl-infra/k8s-workloads/gitlab-helmfiles)
    * GitOps tools
        * [Flux](https://fluxcd.io/flux/get-started/)
        * [Argo CD](https://argo-cd.readthedocs.io/en/stable/getting_started/)
* Инструменты мониторинга
    * [Prometheus](https://prometheus.io/docs/prometheus/latest/getting_started/)
    * [Grafana](https://grafana.com/docs/grafana/latest/getting-started/)
    * [InfluxDB](https://docs.influxdata.com/influxdb/v2/get-started/)
