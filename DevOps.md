# جدول جامع ابزارها و مفاهیم DevOps (نسخه نهایی ۲۰۲۶ - کامل‌ترین مرجع)

| دسته‌بندی | ابزار / فناوری / مفهوم | توضیح مختصر کاربرد |
| :--- | :--- | :--- |
| **📋 برنامه‌ریزی و مدیریت پروژه (Agile/Kanban)** | `Jira`, `Trello`, `Asana`, `Monday.com`, `ClickUp` | مدیریت وظایف، اسپرینت، بورد کانبان، ردیابی issue، هماهنگی تیمی |
| **📊 تحلیل و متریک پروژه** | `Velocity`, `Burndown Chart`, `Cumulative Flow Diagram` | تحلیل پیشرفت تیم، پیش‌بینی زمان تحویل، شناسایی گلوگاه‌ها |
| **💻 مدیریت کد منبع (VCS)** | `Git`, `GitHub`, `GitLab`, `Bitbucket`, `Azure Repos` | کنترل نسخه، مدیریت برنچ، مرور کد، همکاری تیمی |
| **🔧 یکپارچه‌سازی مداوم (CI)** | `GitHub Actions`, `Jenkins`, `GitLab CI`, `CircleCI`, `Bamboo` | ساخت و تست خودکار به ازای هر commit، تحلیل استاتیک |
| **🚀 استقرار مداوم (CD) & GitOps** | `Argo CD`, `Flux`, `Spinnaker`, `Harness`, `Jenkins X` | استقرار خودکار، مدیریت نسخه، هماهنگی با مخزن گیت (GitOps) |
| **🏗️ زیرساخت به‌عنوان کد (IaC)** | `Terraform`, `OpenTofu`, `Pulumi`, `AWS CDK`, `Crossplane` | تعریف ابر، شبکه، دیتابیس با کد، نسخه‌دهی زیرساخت |
| **⚙️ مدیریت پیکربندی (Config Mgmt)** | `Ansible`, `Chef`, `Puppet`, `SaltStack` | نصب و پیکربندی نرم‌افزار روی سرورها، مدیریت یکپارچه محیط |
| **🐳 کانتینری‌سازی** | `Docker`, `Podman`, `containerd`, `LXC/LXD` | ساخت ایمیج، اجرای کانتینر، جداسازی برنامه |
| **📦 رجیستری کانتینر** | `Docker Hub`, `GitHub Container Registry (GHCR)`, `Harbor`, `Amazon ECR`, `Azure ACR`, `Google GCR` | ذخیره و اشتراک ایمیج، اسکن امنیتی |
| **☸️ ارکستریشن کانتینر** | `Kubernetes (K8s)`, `OpenShift` (Red Hat K8s), `Rancher`, `Docker Swarm`, `Nomad` | مدیریت خودکار کانتینرها، مقیاس‌پذیری، تعادل بار، خودترمیمی |
| **🖥️ مدیریت کانتینر (GUI)** | `Portainer`, `Rancher`, `OpenShift Console`, `K9s` (CLI), `Lens` (IDE) | رابط گرافیکی برای مدیریت Docker و Kubernetes، عیب‌یابی ساده‌تر |
| **🌐 پروکسی معکوس و Ingress** | `Traefik`, `Nginx`, `HAProxy`, `Caddy`, `Apache`, `Envoy` | مسیریابی ترافیک، تعادل بار، SSL/TLS termination، API Gateway |
| **📡 DNS سرور** | `PowerDNS`, `Bind9`, `CoreDNS`, `coredns` (K8s native), `dnsmasq` | مدیریت رکوردهای DNS، حل نام دامنه، سرور DNS داخلی |
| **☁️ ابرهای عمومی (Cloud)** | `AWS`, `Microsoft Azure`, `Google Cloud Platform (GCP)` | محاسبات ابری، ذخیره‌سازی، پایگاه داده، AI/ML، serverless |
| **💾 ذخیره‌سازی آبجکت (Object Storage)** | `MinIO`, `AWS S3`, `Azure Blob`, `Google Cloud Storage` | ذخیره فایل، بکاپ، داده‌های حجیم، سازگار با S3 API |
| **🏢 مجازی‌سازی دیتاسنتر** | `Proxmox VE`, `VMware vSphere`, `XCP-ng`, `KVM`, `oVirt` | اجرای ماشین‌های مجازی (VM) و کانتینر (LXC) روی سخت‌افزار فیزیکی، مدیریت خوشه |
| **🏡 فضای ابری شخصی (Self-hosted Cloud)** | `Nextcloud`, `ownCloud`, `Seafile`, `Pydio Cells` | جایگزین Google Drive/Dropbox با قابلیت اشتراک فایل، همگام‌سازی، تقویم و مخاطب |
| **🤖 Ops رویکردهای تخصصی** | `DevOps`, `DevSecOps`, `MLOps`, `LLMOps`, `AIOps`, `FinOps`, `GitOps`, `DataOps`, `NoOps` | فرهنگ و روش‌های عملیاتی در حوزه‌های مختلف (امنیت، یادگیری ماشین، هزینه، داده) |
| **🔐 DevSecOps (امنیت)** | `Falco`, `Kyverno`, `OPA/Gatekeeper`, `Trivy`, `Gitleaks`, `Snyk` | امنیت در کل چرخه حیات، اسکن آسیب‌پذیری، پالیسی as code |
| **🧠 MLOps / LLMOps** | `Kubeflow`, `MLflow`, `BentoML`, `Langfuse`, `OpenLLMetry`, `Ray` | استقرار و مانیتورینگ مدل‌های ML/LLM، tracking آزمایش‌ها |
| **🤖 AIOps** | `BigPanda`, `Moogsoft`, `Dynatrace AI`, `AutoGPT` (تحلیل لاگ) | استفاده از هوش مصنوعی برای تشخیص خودکار ناهنجاری و ریشه‌یابی |
| **💰 FinOps** | `kubecost`, `OpenCost`, `Infracost`, `Vantage`, `CloudHealth` | مدیریت هزینه ابر، تخصیص هزینه به تیم‌ها، بهینه‌سازی |
| **📊 مشاهده‌پذیری (Observability)** | `Prometheus`, `Grafana`, `Loki`, `Tempo`, `Jaeger`, `OpenTelemetry` | متریک، لاگ، تریس، داشبورد، نظارت بر سلامت سیستم |
| **📜 جمع‌آوری و تحلیل لاگ** | `ELK Stack` (Elasticsearch, Logstash, Kibana), `Graylog`, `Fluentd` | متمرکزسازی لاگ، جستجو، تحلیل و هشدار |
| **📡 شبکه پایه (Networking)** | `TCP/IP`, `DNS`, `HTTP/HTTPS`, `Load Balancer`, `Firewall`, `VPC`, `CDN` | مفاهیم پایه شبکه برای ارتباط سرویس‌ها |
| **🖥️ سیستمعامل و اسکریپت** | `Linux (Ubuntu, CentOS, Alpine)`, `Bash`, `Shell Script`, `PowerShell` | مدیریت سرور، خودکارسازی وظایف، عیب‌یابی |
| **🧪 تست نویسی (Testing)** | `Unit Test`, `Integration Test`, `E2E Test`, `Performance Test`, `Security Test` | انواع تست برای تضمین کیفیت نرم‌افزار |
| **🐍 کتابخانه‌های تست پایتون** | `pytest`, `unittest`, `nose2`, `tox`, `mock`, `coverage.py`, `robotframework` | نوشتن تست خودکار، گزارش پوشش کد، تست پارامتری |
| **🌐 تست وب و API** | `Selenium`, `Playwright`, `Cypress`, `Postman/Newman`, `pytest-requests` | تست UI، تست API، اتوماسیون مرورگر |
| **📦 تست بار و عملکرد** | `Locust`, `JMeter`, `k6`, `Gatling`, `Vegeta` | شبیه‌سازی ترافیک سنگین، شناسایی گلوگاه، تست نفوذ |
| **🎓 گواهی‌های پایه و حرفه‌ای (CompTIA & others)** | `A+`, `Network+`, `Security+`, `Linux+`, `Cloud+`, `AWS Certified`, `CKA`, `CKAD` | دانش پایه سخت‌افزار، شبکه، امنیت، لینوکس، ابر، Kubernetes |
| **🗄️ پایگاه داده در DevOps** | `PostgreSQL`, `MySQL`, `MongoDB`, `Redis`, `Cassandra` | مدیریت دیتابیس به عنوان کد، مهاجرت، بکاپ و بازیابی |
| **🔐 مدیریت اسرار (Secrets)** | `HashiCorp Vault`, `Doppler`, `Infisical`, `AWS Secrets Manager` | ذخیره امن رمزها، توکن‌ها، کلیدهای API |
| **🛠️ مهندسی پلتفرم (Platform Engineering)** | `Backstage`, `Crossplane`, `Kratix`, `Humanitec`, `Cortex` | ساخت پلتفرم داخلی برای توسعه‌دهندگان (IDP)، سلف‌سرویس |
| **⚡ مقیاس‌پذیری خودکار** | `KEDA` (event-driven), `Karpenter` (K8s node autoscaling), `HPA`, `VPA` | مقیاس‌گذاری خودکار بر اساس متریک‌ها و رویدادها |