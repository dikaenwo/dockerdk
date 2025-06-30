# Cara Install di VM Mu

1. Clone repository:

   ```bash
   git clone https://github.com/dikaenwo/dockerdk.git
   cd dockerdk
   ```

2. Build image:

   ```bash
   docker build -t portflio-dika-tailwind-nginx .
   ```

3. Jalankan container:

   ```bash
   docker run -d --name portfolio-dika-tailwind -p 7676:7676 portflio-dika-tailwind-nginx
   ```
