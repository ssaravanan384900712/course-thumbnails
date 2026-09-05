# Course Thumbnails

AI-generated Udemy video thumbnails for all courses by **Saravanan Sundaramoorthy** ([saravanansun.com](https://saravanansun.com)).

Generated with **MAI-Image-2.6-Flash** (Azure AI). Stored with Git LFS (1280×768 JPEG, ~1.2 MB each).

**Total: 471 thumbnails across 4 courses**

## Courses

| Course | Thumbnails |
|--------|-----------|
| [apache_kafka_mastery](https://github.com/ssaravanan384900712/course-thumbnails/tree/main/apache_kafka_mastery) | 70 |
| [k8s_masterclass](https://github.com/ssaravanan384900712/course-thumbnails/tree/main/k8s_masterclass) | 170 |
| [pulumi_iac](https://github.com/ssaravanan384900712/course-thumbnails/tree/main/pulumi_iac) | 65 |
| [terraform_multicloud](https://github.com/ssaravanan384900712/course-thumbnails/tree/main/terraform_multicloud) | 166 |

## Regenerating

All prompts are stored in each course's `thumbnails/prompts_manifest.json` in the main repo:
[terraform-4days-training](https://github.com/ssaravanan384900712/terraform-4days-training)

To regenerate a course:
```bash
python3 <course>/workfiles/.generate_thumbnails.py
python3 sync_thumbnails_to_lfs.py
```
