# Image Pipeline

This repository stores image batches and processed output for Charlie's World.

## Folder flow

```text
image-pipeline/inbox/<project>/<asset-type>/<batch>
image-pipeline/processing/<run-id>
image-pipeline/processed/accepted
image-pipeline/processed/review
image-pipeline/processed/rejected
image-pipeline/archive/originals/<run-id>
image-pipeline/reports/<run-id>
image-pipeline/previews/<run-id>
```

## First test batch

The Runner01 workflow can generate synthetic test images in:

```text
image-pipeline/inbox/gizmo-adventure/logos/test-batch
```

Processed outputs are uploaded as a workflow artifact. If cross-repo commit is later enabled with a PAT, results can also be committed back here.
