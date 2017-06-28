# ansible-maker

Installs MAKER v2.31.9:
  - NCBI Blast+ v2.6.0
  - SNAP
  - TRF v4.09
  - RepeatMasker v4.0.6
  - Exonerate v2.2.0
  - Augustus v3.2.3

### Varables

| Variable                | Required | Default | Choices                   | Comments                                   |
|-------------------------|----------|---------|---------------------------|--------------------------------------------|
| MAKER_HOME              | yes      | /home/MAKER   |         | Directory with enough space. Also where other MAKER dependencies are installed |
| MAKER_FILE              | yes      | "maker-2.31.9.tgz"   |         | User must provide their own maker source files and put them in the `files/` directory |
| MAKER_URL               | yes      | None   |         | User must provide their own maker source files. If the user doesn't have file, they can use a URL |
