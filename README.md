Based largely off of the work of the Brilliant people who worked on the ShowUI ecosystem of models, created to increase accuracy and reduce large training workloads for a course Project...


WIP

to run simply navigate to the ShowUI.Showui Directory (where we see train_click_nav)

and run it using python train_click_nav.py or more specifically This should work... python -m model.showui.train_click_nav --model_name_or_path qwen2_vl_2b --output_dir model/showui/osproject/click_nav_ckpt --epochs 10 --train_batch_size 1 --grad_accum 8 --fp16
