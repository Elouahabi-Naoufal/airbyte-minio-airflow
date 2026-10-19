<a id="readme-top"></a>

[![Contributors][contributors-shield]][contributors-url]
[![Forks][forks-shield]][forks-url]
[![Stargazers][stars-shield]][stars-url]
[![Issues][issues-shield]][issues-url]
[![LinkedIn][linkedin-shield]][linkedin-url]

<br />
<div align="center">
  <a href="https://github.com/Elouahabi-Naoufal/airbyte-minio-airflow">
    <h3 align="center">Airbyte, MinIO and Airflow</h3>
  </a>

  <p align="center">
    Planned containerised extract-load pipeline using Airbyte, MinIO object storage and Airflow orchestration.
    <br />
    <a href="https://github.com/Elouahabi-Naoufal/airbyte-minio-airflow"><strong>Explore the repository »</strong></a>
    <br />
    <br />
    <a href="https://github.com/Elouahabi-Naoufal/airbyte-minio-airflow/issues/new?labels=bug">Report Bug</a>
    &middot;
    <a href="https://github.com/Elouahabi-Naoufal/airbyte-minio-airflow/issues/new?labels=enhancement">Request Feature</a>
  </p>
</div>

<details>
  <summary>Table of Contents</summary>
  <ol>
    <li><a href="#about-the-project">About The Project</a>
      <ul><li><a href="#built-with">Built With</a></li></ul>
    </li>
    <li><a href="#getting-started">Getting Started</a>
      <ul>
        <li><a href="#prerequisites">Prerequisites</a></li>
        <li><a href="#installation">Installation</a></li>
      </ul>
    </li>
    <li><a href="#usage">Usage</a></li>
    <li><a href="#roadmap">Roadmap</a></li>
    <li><a href="#contributing">Contributing</a></li>
    <li><a href="#license">License</a></li>
    <li><a href="#contact">Contact</a></li>
    <li><a href="#acknowledgments">Acknowledgments</a></li>
  </ol>
</details>

## About The Project

This repository is the project space for a fourth-year PFM project at EMSI (semester S2): a containerised extract-load pipeline that moves data from a source system into MinIO object storage, with Airflow orchestrating the runs.

The intended stack is Airbyte for connectors and replication, MinIO as the S3-compatible landing zone, Airflow for scheduling and monitoring, and Docker Compose for the local environment. The repository is currently a scaffold: it contains only a `.gitkeep` placeholder and no implementation.

* Extract and load: Airbyte connectors and replication jobs.
* Landing zone: MinIO object storage.
* Orchestration: Apache Airflow.
* Runtime: Docker Compose.

<p align="right">(<a href="#readme-top">back to top</a>)</p>

### Built With

This repository is currently a scaffold, so no stack is wired up yet. The planned stack is:

* [![Airbyte][airbyte-badge]][airbyte-url]
* [![MinIO][minio-badge]][minio-url]
* [![Apache Airflow][airflow-badge]][airflow-url]
* [![Docker][docker-badge]][docker-url]

<p align="right">(<a href="#readme-top">back to top</a>)</p>

## Getting Started

The repository has no runnable code yet. The steps below only set up a local checkout for future work.

### Prerequisites

* Git
* The toolchain for the planned stack, installed when the implementation starts.

### Installation

1. Clone the repo
   ```sh
   git clone https://github.com/Elouahabi-Naoufal/airbyte-minio-airflow.git
   cd airbyte-minio-airflow
   ```

2. There is nothing to install or start at this stage.

<p align="right">(<a href="#readme-top">back to top</a>)</p>

## Usage

There is no executable code in this repository. It currently serves as the project space for the
work described above; the usage instructions will be added together with the implementation.

<p align="right">(<a href="#readme-top">back to top</a>)</p>

## Roadmap

- [x] Create the repository scaffold.
- [ ] Write the Docker Compose stack for Airbyte, MinIO and Airflow.
- [ ] Define the source connector and the MinIO destination.
- [ ] Add the Airflow DAG that triggers and monitors the sync.
- [ ] Document the bucket layout and the run procedure.

See the [open issues](https://github.com/Elouahabi-Naoufal/airbyte-minio-airflow/issues) for a full list of proposed features (and known issues).

<p align="right">(<a href="#readme-top">back to top</a>)</p>

## Contributing

Contributions are what make the open source community such an amazing place to learn, inspire, and create. Any contributions you make are **greatly appreciated**.

If you have a suggestion that would make this better, please fork the repo and create a pull request. You can also simply open an issue with the tag "enhancement".
Don't forget to give the project a star! Thanks again!

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

### Top contributors:

<a href="https://github.com/Elouahabi-Naoufal/airbyte-minio-airflow/graphs/contributors">
  <img src="https://contrib.rocks/image?repo=Elouahabi-Naoufal/airbyte-minio-airflow" alt="contrib.rocks image" />
</a>

<p align="right">(<a href="#readme-top">back to top</a>)</p>

## License

This project is not licensed — all rights reserved.

<p align="right">(<a href="#readme-top">back to top</a>)</p>

## Contact

Naoufal Elouahabi - [LinkedIn](https://www.linkedin.com/in/elouahabi-naoufal/) - elouahabi-naoufal1@gmail.com

Project Link: [https://github.com/Elouahabi-Naoufal/airbyte-minio-airflow](https://github.com/Elouahabi-Naoufal/airbyte-minio-airflow)

<p align="right">(<a href="#readme-top">back to top</a>)</p>

## Acknowledgments

* [Airbyte Documentation](https://docs.airbyte.com/)
* [MinIO Documentation](https://min.io/docs/minio/linux/index.html)
* [Apache Airflow Documentation](https://airflow.apache.org/docs/)
* [Img Shields](https://shields.io)
* [Choose an Open Source License](https://choosealicense.com)
* [Best-README-Template](https://github.com/othneildrew/Best-README-Template)

<p align="right">(<a href="#readme-top">back to top</a>)</p>

[contributors-shield]: https://img.shields.io/github/contributors/Elouahabi-Naoufal/airbyte-minio-airflow.svg?style=for-the-badge
[contributors-url]: https://github.com/Elouahabi-Naoufal/airbyte-minio-airflow/graphs/contributors
[forks-shield]: https://img.shields.io/github/forks/Elouahabi-Naoufal/airbyte-minio-airflow.svg?style=for-the-badge
[forks-url]: https://github.com/Elouahabi-Naoufal/airbyte-minio-airflow/network/members
[stars-shield]: https://img.shields.io/github/stars/Elouahabi-Naoufal/airbyte-minio-airflow.svg?style=for-the-badge
[stars-url]: https://github.com/Elouahabi-Naoufal/airbyte-minio-airflow/stargazers
[issues-shield]: https://img.shields.io/github/issues/Elouahabi-Naoufal/airbyte-minio-airflow.svg?style=for-the-badge
[issues-url]: https://github.com/Elouahabi-Naoufal/airbyte-minio-airflow/issues
[linkedin-shield]: https://img.shields.io/badge/-LinkedIn-black.svg?style=for-the-badge&logo=linkedin&colorB=555
[linkedin-url]: https://www.linkedin.com/in/elouahabi-naoufal/
[airbyte-badge]: https://img.shields.io/badge/Airbyte-615EFF?style=for-the-badge&logo=airbyte&logoColor=white
[airbyte-url]: https://airbyte.com/
[minio-badge]: https://img.shields.io/badge/MinIO-C72E49?style=for-the-badge&logo=minio&logoColor=white
[minio-url]: https://min.io/
[airflow-badge]: https://img.shields.io/badge/Apache%20Airflow-017CEE?style=for-the-badge&logo=apacheairflow&logoColor=white
[airflow-url]: https://airflow.apache.org/
[docker-badge]: https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white
[docker-url]: https://www.docker.com/
