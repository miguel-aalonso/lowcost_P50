# lowcost_P50
A low-cost protocol for the optical method of vulnerability curves to calculate drought resistance in plants

Water stress significantly impacts the productivity of natural and agricultural ecosystems, often leading to plant death by triggering physiological responses that limit carbon intake and metabolism. Some species are more drought-resistant than others, and understanding this resistance helps predict species distribution and select better-suited plants for restoration or agriculture. However, measuring water stress in an accurate and practical way remains a challenge.

Plants transport water through a tension-cohesion mechanism, where water moves from roots to leaves under negative pressure. When soil water is scarce, this pressure increases, causing xylem damage through air bubbles (embolisms) that block water flow, potentially leading to plant death. The water potential at which 50% of hydraulic conductivity is lost (P50) is a key measure of drought resistance derived from vulnerability curves that show the relationship between water potential and conductivity loss.

Methods to measure P50 vary in cost and complexity. The bench drying method is the most accessible for desiccation, while conductivity loss can be measured hydraulically or visually. Visual methods, like microtomography and optical techniques, are promising but often expensive. A newer optical method uses light transmission changes to detect embolisms, but current setups are costly and not widely accessible.

To address this, we propose a low-cost optical method using USB microscopes and simple tools to measure P50 in stems. This approach is designed to be affordable and applicable in resource-limited regions, particularly in biodiversity-rich areas of the global South. We validated the method by comparing P50 in two contrasting woody species and evaluated its cost-effectiveness.

This is the accompanying GitHub page for the article "*A low-cost protocol for the optical method of vulnerability curves to calculate P50*" submitted to the Journal *Applications in Plant Sciences*. This repository contains the Python source code required to operate the USB microscopes used in the protocol.

The file **materials_and_methods.md** contains the protocol for preparing plants and obtaining water potential. It includes a link to all the products/items used in the experiment.

The files *calibrate_camera_Journal_version.py* and *camera_image_acquisition_Journal_version.py* contain the Python source code to replicate the results presented in the journal article.
