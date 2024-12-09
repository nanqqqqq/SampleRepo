# SampleRepo

This sample repository provides a well-structured template for organizing projects. Below is the detailed description of each folder and file and its intended purpose.

## Directory Structure

<table>
  <thead>
    <tr>
      <th>Folder/File</th>
      <th>Description</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td><code>data/</code></td>
      <td>
        Stores raw or processed data files used in the project. This folder is for external datasets, input data, or intermediary processed data that are not directly tied to the codebase.
        <br> In an ideal production environment, data should always be retrieved from a database or storage, rather than directly from this folder.
      </td>
    </tr>
    <tr>
      <td><code>models/</code></td>
      <td>
        Contains trained model files, checkpoints, and configurations. It is primarily used for storing outputs from machine learning pipelines.
        <br> In an ideal production environment, trained model should be saved in storage, rather than directly in this folder.
      </td>
    </tr>
    <tr>
      <td><code>notebooks/</code></td>
      <td>
        Holds Jupyter Notebooks for exploratory data analysis (EDA), experimentation, and result reporting. Typically used for prototyping and quick iterations.
        <br> Not required in production environment.
      </td>
    </tr>
    <tr>
      <td><code>docs/</code></td>
      <td>
        Documentation files, architecture diagrams, and references related to the project. This folder serves as the resource for understanding the project's structure and purpose.
      </td>
    </tr>
    <tr>
      <td><code>scripts/</code></td>
      <td>
        Contains standalone executable scripts for tasks such as data preprocessing, model training, and evaluation.
      </td>
    </tr>
    <tr>
      <td><code>tests/</code></td>
      <td>
        Includes unit tests and integration tests to validate code functionality. These tests ensure the correctness and stability of the codebase.
      </td>
    </tr>
    <tr>
      <td><code>utils/</code></td>
      <td>
        Utility functions, shared helper scripts, or modules that can be reused across different parts of the project. Examples include metrics calculations, data visualizations, and logging utilities.
      </td>
    </tr>
    <tr>
      <td><code>src/</code></td>
      <td>
        The main source code directory containing the core implementation of the project. All business logic, including data loading, model definitions, and pipelines, resides here.
      </td>
    </tr>
    <tr>
      <td><code>src/data/</code></td>
      <td>
        Contains data loading and preprocessing logic (code). Unlike the top-level <code>data/</code> folder, this is not for storing actual data files but for Python scripts or modules that handle data transformations, loading, and validation.
      </td>
    </tr>
    <tr>
      <td><code>src/models/</code></td>
      <td>
        Contains Python scripts or modules for defining, training, and evaluating machine learning models. 
      </td>
    </tr>
    <tr>
      <td><code>src/utils/</code></td>
      <td>
        Utility scripts or helper functions specific to the core implementation. These functions might include model-related utilities, such as checkpoint handling or parameter management.
      </td>
    </tr>
    <tr>
      <td><code>__init__.py</code></td>
      <td>
        Marks the corresponding directory as a Python package. It allows models to be imported from other parts of the project.
      </td>
    </tr>
    <tr>
      <td><code>requirements.txt</code></td>
      <td>
        A file listing all the Python dependencies required for the project. It is used for setting up the project environment. Example usage:
        <pre><code>pip install -r requirements.txt</code></pre>
      </td>
    </tr>
  </tbody>
</table>