..
    This file is part of GEO Knowledge Hub.
    Copyright 2020 GEO Secretariat.

    GEO Knowledge Hub is free software; you can redistribute it and/or modify it
    under the terms of the MIT License; see LICENSE file for more details.


Repository Organization
=======================


Overview
--------

Following is an overview of the files and folders:


.. table::

    +-----------------------------+------------------------------------------------------------------------------+
    | Name                        | Description                                                                  |
    +=============================+==============================================================================+
    | ``Dockerfile``              | Dockerfile used to build your application image.                             |
    +-----------------------------+------------------------------------------------------------------------------+
    | ``Pipfile``                 | Python requirements installed via [pipenv](https://pipenv.pypa.io)           |
    +-----------------------------+------------------------------------------------------------------------------+
    | ``Pipfile.lock``            | Locked requirements (generated on first install).                            |
    +-----------------------------+------------------------------------------------------------------------------+
    | ``app_data``                | Application data such as vocabularies.                                       |
    +-----------------------------+------------------------------------------------------------------------------+
    | ``assets``                  | Web assets (CSS, JavaScript, LESS, JSX templates) used in the Webpack build. |
    +-----------------------------+------------------------------------------------------------------------------+
    | ``docker``                  | Example configuration for NGINX and uWSGI.                                   |
    +-----------------------------+------------------------------------------------------------------------------+
    | ``docs``                    | Sphinx based documentation folder.                                           |
    +-----------------------------+------------------------------------------------------------------------------+
    | ``docker-compose.full.yml`` | Example of a full infrastructure stack.                                      |
    +-----------------------------+------------------------------------------------------------------------------+
    | ``docker-compose.yml``      | Backend services needed for local development.                               |
    +-----------------------------+------------------------------------------------------------------------------+
    | ``docker-services.yml``     | Common services for the Docker Compose files.                                |
    +-----------------------------+------------------------------------------------------------------------------+
    | ``invenio.cfg``             | The Invenio application configuration.                                       |
    +-----------------------------+------------------------------------------------------------------------------+
    | ``logs``                    | Log files.                                                                   |
    +-----------------------------+------------------------------------------------------------------------------+
    | ``static``                  | Static files that need to be served as-is (e.g. images).                     |
    +-----------------------------+------------------------------------------------------------------------------+
    | ``templates``               | Folder for your Jinja templates.                                             |
    +-----------------------------+------------------------------------------------------------------------------+
    | ``.invenio``                | Common file used by Invenio-CLI to be version controlled.                    |
    +-----------------------------+------------------------------------------------------------------------------+
    | ``.invenio.private``        | Private file used by Invenio-CLI (must be created per machine installation). |
    +-----------------------------+------------------------------------------------------------------------------+
