# analystBase_qorix_incubDeployment

# AnalystBase: A Modern Business Intelligence Frontend

[![Build Status](https://img.shields.io/travis/com/user/repo.svg)](https://travis-ci.com/user/repo)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

This repository contains the source code for the AnalystBase frontend, a powerful, open-source analytics and business intelligence platform built with React. It provides a rich, interactive user interface for data exploration, visualization, and dashboard creation.

---

## ✨ Key Features

* **Interactive Visualizations**: A rich set of visualizations to explore and present data in a meaningful way.
* **Extensible Plugin Architecture**: A robust plugin system allows for custom visualizations, drivers, and functionality. The code supports both built-in and Enterprise-level plugins.
* **Advanced State Management**: Utilizes Redux for predictable and centralized state management across the application.
* **Modern UI Toolkit**: Built with the **Mantine** component library and **Emotion** for styling, ensuring a polished and responsive user experience.
* **Embedding Capabilities**: Supports embedding questions and dashboards seamlessly into other applications.
* **Drag-and-Drop Interface**: Uses React DnD for intuitive interactions, such as building dashboards.

---

## 🛠️ Tech Stack

* **Core Framework**: React
* **State Management**: Redux & React Redux
* **Routing**: React Router
* **UI Library**: Mantine UI
* **Styling**: Emotion
* **Drag & Drop**: React DnD
* **Date/Time**: Day.js
* **Build Tool**: Webpack (inferred)

---

## 🚀 Getting Started

Follow these instructions to set up and run the project on your local machine for development and testing purposes.

### Prerequisites

You will need [Node.js](https://nodejs.org/) (version 18.x or newer is recommended) and a package manager like [npm](https://www.npmjs.com/) or [yarn](https://yarnpkg.com/).

### Installation & Setup

1.  **Clone the repository:**
    ```bash
    git clone [https://github.com/your-username/analystbase.git](https://github.com/your-username/analystbase.git)
    cd analystbase
    ```

2.  **Install dependencies:**
    ```bash
    npm install
    ```
    or if you use yarn:
    ```bash
    yarn install
    ```

3.  **Configure Environment Variables:**
    This project likely requires a backend server to function. You may need to create a `.env` file in the root of the project to configure the API endpoint. Look for a `.env.example` file for guidance.
    ```
    API_HOST=http://localhost:3000
    ```

4.  **Run the development server:**
    ```bash
    npm start
    ```
    The application should now be running on `http://localhost:PORT` (the port will be specified in your project's configuration).

---

## 📁 Project Structure

The codebase is organized with a clear separation of concerns, leveraging a modular structure.
## Structure
analystBase_qorix_incubDeployment-main/
    .cljfmt.edn
    .dir-locals.el
    .dockerignore
    .editorconfig
    .eslintignore
    .eslintrc.js
    .gitignore
    .lycheeignore
    .mlc_config.json
    .nvmrc
    .pre-commit-config.yaml
    .prettierignore
    .prettierrc
    .stylelintrc.json
    .yarnrc
    Dockerfile
    LICENSE-AGPL.txt
    LICENSE-EMBEDDING.txt
    LICENSE-MCL.txt
    LICENSE.txt
    README.md
    babel.config.json
    bad-blobs.txt
    bb.edn
    blob_ids.txt
    codecov.yml
    config.yml.sample
    cypress.env.json.example
    deps.edn
    jest.config.js
    jest.tz.unit.conf.json
    linux-install-1.11.1.1413.sh
    loki.config.js
    package.json
    postcss.config.js
    rspack.config.js
    rspack.embedding-sdk-bundle.config.js
    rspack.embedding-sdk-cli.config.js
    rspack.embedding-sdk-package.config.js
    rspack.iframe-sdk-embed.config.js
    rspack.main.config.js
    rspack.shared.config.js
    rspack.static-viz.config.js
    shadow-cljs.edn
    tsconfig.base.json
    tsconfig.json
    tsconfig.sdk.json
    yarn.lock

    .claude/
        commands/
            fix-flakey-test.md
            fix-issue.md
            fix-pr.md
            repro-issue.md

    .clj-kondo/
        README.md
        config.edn
        config/
            modules/config.edn
            test-helpers/config.edn
        macros/
            quartz.clj
            metabase/
                collections/api_test.clj
                embedding/api/embed_test.clj
                lib/common.clj
                lib/filter.clj
                parameters/chain_filter_test.clj
                public_sharing/api_test.clj
                queries/api/card_test.clj
                query_analysis/models/query_analysis_test.clj
                query_analysis/task/test_setup.clj
                query_processor/streaming.clj
                server/statistics_handler_test.clj
                test/util.clj
                test/data/users.clj
                users/models/user_test.clj
                util/namespaces.clj
                xrays/related_test.clj
                xrays/domain_entities/malli.clj
        metabase_enterprise/
            database_routing/e2e_test.clj
            impersonation/util_test.clj
            query_reference_validation/api_test.clj
            sandbox/test_util.clj
            serialization/test_util.clj
        src/hooks/
            common.clj
            clojure/test.clj

