tech-identifier-app/
│
├── backend/              # Backend (Server-Side)
│   ├── data/
│   │   ├── categories.json
│   │   ├── groups.json
│   │   ├── technologies/
│   │       ├── tech_1.json
│   │       ├── tech_2.json
│   │       ├── ...
│   │       ├── identified_technologies.json
│   ├── scripts/
│   │   ├── category_validator.py
│   │   ├── group_validator.py
│   │   ├── structure_validator.py
│   │   ├── technology_identifier.py
│   │   ├── technology_validator.py
│   │   ├── tech_list_matrix_generator.py
│   │   ├── technology_report_generator.py
│   └── app.py            # Backend Application

├── frontend/             # Frontend (Client-Side)
│   ├── src/
│   │   ├── components/
│   │   │   ├── TechIdentificationForm.vue
│   │   │   ├── TechReport.vue
│   │   ├── App.vue
│   │   ├── main.js
│   └── public/
│   └── package.json
│   └── README.md
│   └── ...

├── README.md

