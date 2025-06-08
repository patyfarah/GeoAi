# GeoAi
Geo AI projects
the AI-project-2025 aim to test the Sample4GEO platform.
You can download the notebook and run it directly in google colab.
The data and Code will be installed from their host location.
You only need to run the code in sequence.
After all is run:
1- You can remove the zip files
2- You need to rename the University- folder under Sample4Geo/data to U1652
3- Adjust in the eval-university.py file by replacing ./ by /content/Sample4GEO for all paths to ensure reading from the data folder.

Result excpected:
------------------------------[University-1652]------------------------------
Extract Features:
  0% 0/296 [00:00<?, ?it/s]/content/Sample4Geo/sample4geo/trainer.py:134: FutureWarning: `torch.cuda.amp.autocast(args...)` is deprecated. Please use `torch.amp.autocast('cuda', args...)` instead.
  with autocast():
100% 296/296 [06:35<00:00,  1.34s/it]
100% 8/8 [00:14<00:00,  1.82s/it]
Compute Scores:
100% 37855/37855 [00:18<00:00, 2026.64it/s]
Recall@1: 92.6483 - Recall@5: 97.6859 - Recall@10: 98.2407 - Recall@top1: 98.2856 - AP: 93.8051

Enjoy!
