train:
CUDA_VISIBLE_DEVICES=0,1,2,3 python bts_main.py args_train_Carla.txt
test:
1. python bts_test.py args_test_Carla_easy.txt
2. python eval_with_pngs.py --pred_path /home/whn/PycharmProjects/DepthPrediction/bts/script/result_bts_carla_easy/raw/ --gt_path /media/whn/新加卷/dataset/carla/Data/test_easy/depth --dataset carla --min_depth_eval 0.6 --max_depth_eval 235.0