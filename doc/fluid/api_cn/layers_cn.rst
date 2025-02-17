.. _cn_api_fluid_layers:

=======================
fluid.layers
=======================




..  toctree::
    :maxdepth: 1

    layers_cn/abs_cn.rst
    layers_cn/accuracy_cn.rst
    layers_cn/acos_cn.rst
    layers_cn/adaptive_pool2d_cn.rst
    layers_cn/adaptive_pool3d_cn.rst
    layers_cn/add_position_encoding_cn.rst
    layers_cn/affine_channel_cn.rst
    layers_cn/affine_grid_cn.rst
    layers_cn/anchor_generator_cn.rst
    layers_cn/argmax_cn.rst
    layers_cn/argmin_cn.rst
    layers_cn/argsort_cn.rst
    layers_cn/array_length_cn.rst
    layers_cn/array_read_cn.rst
    layers_cn/array_write_cn.rst
    layers_cn/asin_cn.rst
    layers_cn/assign_cn.rst
    layers_cn/atan_cn.rst
    layers_cn/auc_cn.rst
    layers_cn/autoincreased_step_counter_cn.rst
    layers_cn/batch_norm_cn.rst
    layers_cn/beam_search_cn.rst
    layers_cn/beam_search_decode_cn.rst
    layers_cn/bilinear_tensor_product_cn.rst
    layers_cn/bipartite_match_cn.rst
    layers_cn/box_clip_cn.rst
    layers_cn/box_coder_cn.rst
    layers_cn/box_decoder_and_assign_cn.rst
    layers_cn/bpr_loss_cn.rst
    layers_cn/brelu_cn.rst
    layers_cn/cast_cn.rst
    layers_cn/ceil_cn.rst
    layers_cn/center_loss_cn.rst
    layers_cn/chunk_eval_cn.rst
    layers_cn/clip_by_norm_cn.rst
    layers_cn/clip_cn.rst
    layers_cn/collect_fpn_proposals_cn.rst
    layers_cn/concat_cn.rst
    layers_cn/continuous_value_model_cn.rst
    layers_cn/conv2d_cn.rst
    layers_cn/conv2d_transpose_cn.rst
    layers_cn/conv3d_cn.rst
    layers_cn/conv3d_transpose_cn.rst
    layers_cn/cos_cn.rst
    layers_cn/cos_sim_cn.rst
    layers_cn/cosine_decay_cn.rst
    layers_cn/create_array_cn.rst
    layers_cn/create_global_var_cn.rst
    layers_cn/create_parameter_cn.rst
    layers_cn/create_py_reader_by_data_cn.rst
    layers_cn/create_tensor_cn.rst
    layers_cn/crf_decoding_cn.rst
    layers_cn/crop_cn.rst
    layers_cn/crop_tensor_cn.rst
    layers_cn/cross_entropy_cn.rst
    layers_cn/ctc_greedy_decoder_cn.rst
    layers_cn/cumsum_cn.rst
    layers_cn/data_cn.rst
    layers_cn/data_norm_cn.rst
    layers_cn/deformable_conv_cn.rst
    layers_cn/deformable_roi_pooling_cn.rst
    layers_cn/density_prior_box_cn.rst
    layers_cn/detection_map_cn.rst
    layers_cn/detection_output_cn.rst
    layers_cn/diag_cn.rst
    layers_cn/dice_loss_cn.rst
    layers_cn/distribute_fpn_proposals_cn.rst
    layers_cn/double_buffer_cn.rst
    layers_cn/dropout_cn.rst
    layers_cn/dynamic_gru_cn.rst
    layers_cn/dynamic_lstm_cn.rst
    layers_cn/dynamic_lstmp_cn.rst
    layers_cn/DynamicRNN_cn.rst
    layers_cn/edit_distance_cn.rst
    layers_cn/elementwise_add_cn.rst
    layers_cn/elementwise_div_cn.rst
    layers_cn/elementwise_floordiv_cn.rst
    layers_cn/elementwise_max_cn.rst
    layers_cn/elementwise_min_cn.rst
    layers_cn/elementwise_mod_cn.rst
    layers_cn/elementwise_mul_cn.rst
    layers_cn/elementwise_pow_cn.rst
    layers_cn/elementwise_sub_cn.rst
    layers_cn/elu_cn.rst
    layers_cn/embedding_cn.rst
    layers_cn/equal_cn.rst
    layers_cn/exp_cn.rst
    layers_cn/expand_cn.rst
    layers_cn/exponential_decay_cn.rst
    layers_cn/eye_cn.rst
    layers_cn/fc_cn.rst
    layers_cn/fill_constant_batch_size_like_cn.rst
    layers_cn/fill_constant_cn.rst
    layers_cn/filter_by_instag_cn.rst
    layers_cn/flatten_cn.rst
    layers_cn/floor_cn.rst
    layers_cn/fsp_matrix_cn.rst
    layers_cn/gather_cn.rst
    layers_cn/gather_nd_cn.rst
    layers_cn/gaussian_random_batch_size_like_cn.rst
    layers_cn/gaussian_random_cn.rst
    layers_cn/generate_mask_labels_cn.rst
    layers_cn/generate_proposal_labels_cn.rst
    layers_cn/generate_proposals_cn.rst
    layers_cn/get_tensor_from_selected_rows_cn.rst
    layers_cn/greater_equal_cn.rst
    layers_cn/greater_than_cn.rst
    layers_cn/grid_sampler_cn.rst
    layers_cn/group_norm_cn.rst
    layers_cn/gru_unit_cn.rst
    layers_cn/hard_shrink_cn.rst
    layers_cn/hard_sigmoid_cn.rst
    layers_cn/hard_swish_cn.rst
    layers_cn/has_inf_cn.rst
    layers_cn/has_nan_cn.rst
    layers_cn/hash_cn.rst
    layers_cn/hsigmoid_cn.rst
    layers_cn/huber_loss_cn.rst
    layers_cn/IfElse_cn.rst
    layers_cn/im2sequence_cn.rst
    layers_cn/image_resize_cn.rst
    layers_cn/image_resize_short_cn.rst
    layers_cn/increment_cn.rst
    layers_cn/inverse_time_decay_cn.rst
    layers_cn/iou_similarity_cn.rst
    layers_cn/is_empty_cn.rst
    layers_cn/isfinite_cn.rst
    layers_cn/kldiv_loss_cn.rst
    layers_cn/l2_normalize_cn.rst
    layers_cn/label_smooth_cn.rst
    layers_cn/layer_norm_cn.rst
    layers_cn/leaky_relu_cn.rst
    layers_cn/less_equal_cn.rst
    layers_cn/less_than_cn.rst
    layers_cn/linear_chain_crf_cn.rst
    layers_cn/linear_lr_warmup_cn.rst
    layers_cn/linspace_cn.rst
    layers_cn/load_cn.rst
    layers_cn/lod_append_cn.rst
    layers_cn/lod_reset_cn.rst
    layers_cn/log_cn.rst
    layers_cn/log_loss_cn.rst
    layers_cn/logical_and_cn.rst
    layers_cn/logical_not_cn.rst
    layers_cn/logical_or_cn.rst
    layers_cn/logical_xor_cn.rst
    layers_cn/logsigmoid_cn.rst
    layers_cn/lrn_cn.rst
    layers_cn/lstm_cn.rst
    layers_cn/lstm_unit_cn.rst
    layers_cn/margin_rank_loss_cn.rst
    layers_cn/matmul_cn.rst
    layers_cn/maxout_cn.rst
    layers_cn/mean_cn.rst
    layers_cn/mean_iou_cn.rst
    layers_cn/merge_selected_rows_cn.rst
    layers_cn/mul_cn.rst
    layers_cn/multi_box_head_cn.rst
    layers_cn/multiclass_nms_cn.rst
    layers_cn/multiplex_cn.rst
    layers_cn/natural_exp_decay_cn.rst
    layers_cn/nce_cn.rst
    layers_cn/noam_decay_cn.rst
    layers_cn/Normal_cn.rst
    layers_cn/not_equal_cn.rst
    layers_cn/npair_loss_cn.rst
    layers_cn/one_hot_cn.rst
    layers_cn/ones_cn.rst
    layers_cn/ones_like_cn.rst
    layers_cn/pad_cn.rst
    layers_cn/pad_constant_like_cn.rst
    layers_cn/pad2d_cn.rst
    layers_cn/piecewise_decay_cn.rst
    layers_cn/pixel_shuffle_cn.rst
    layers_cn/polygon_box_transform_cn.rst
    layers_cn/polynomial_decay_cn.rst
    layers_cn/pool2d_cn.rst
    layers_cn/pool3d_cn.rst
    layers_cn/pow_cn.rst
    layers_cn/prelu_cn.rst
    layers_cn/Print_cn.rst
    layers_cn/prior_box_cn.rst
    layers_cn/psroi_pool_cn.rst
    layers_cn/py_func_cn.rst
    layers_cn/py_reader_cn.rst
    layers_cn/random_crop_cn.rst
    layers_cn/range_cn.rst
    layers_cn/rank_cn.rst
    layers_cn/rank_loss_cn.rst
    layers_cn/read_file_cn.rst
    layers_cn/reciprocal_cn.rst
    layers_cn/reduce_all_cn.rst
    layers_cn/reduce_any_cn.rst
    layers_cn/reduce_max_cn.rst
    layers_cn/reduce_mean_cn.rst
    layers_cn/reduce_min_cn.rst
    layers_cn/reduce_prod_cn.rst
    layers_cn/reduce_sum_cn.rst
    layers_cn/relu_cn.rst
    layers_cn/relu6_cn.rst
    layers_cn/reorder_lod_tensor_by_rank_cn.rst
    layers_cn/reshape_cn.rst
    layers_cn/resize_bilinear_cn.rst
    layers_cn/resize_nearest_cn.rst
    layers_cn/resize_trilinear_cn.rst
    layers_cn/retinanet_detection_output_cn.rst
    layers_cn/retinanet_target_assign_cn.rst
    layers_cn/reverse_cn.rst
    layers_cn/roi_align_cn.rst
    layers_cn/roi_perspective_transform_cn.rst
    layers_cn/roi_pool_cn.rst
    layers_cn/round_cn.rst
    layers_cn/row_conv_cn.rst
    layers_cn/rpn_target_assign_cn.rst
    layers_cn/rsqrt_cn.rst
    layers_cn/sampled_softmax_with_cross_entropy_cn.rst
    layers_cn/sampling_id_cn.rst
    layers_cn/scale_cn.rst
    layers_cn/scatter_cn.rst
    layers_cn/scatter_nd_add_cn.rst
    layers_cn/scatter_nd_cn.rst
    layers_cn/selu_cn.rst
    layers_cn/sequence_concat_cn.rst
    layers_cn/sequence_conv_cn.rst
    layers_cn/sequence_enumerate_cn.rst
    layers_cn/sequence_expand_as_cn.rst
    layers_cn/sequence_expand_cn.rst
    layers_cn/sequence_first_step_cn.rst
    layers_cn/sequence_last_step_cn.rst
    layers_cn/sequence_mask_cn.rst
    layers_cn/sequence_pad_cn.rst
    layers_cn/sequence_pool_cn.rst
    layers_cn/sequence_reshape_cn.rst
    layers_cn/sequence_reverse_cn.rst
    layers_cn/sequence_scatter_cn.rst
    layers_cn/sequence_slice_cn.rst
    layers_cn/sequence_softmax_cn.rst
    layers_cn/sequence_unpad_cn.rst
    layers_cn/shape_cn.rst
    layers_cn/shard_index_cn.rst
    layers_cn/shuffle_channel_cn.rst
    layers_cn/shuffle_cn.rst
    layers_cn/sigmoid_cn.rst
    layers_cn/sigmoid_cross_entropy_with_logits_cn.rst
    layers_cn/sigmoid_focal_loss_cn.rst
    layers_cn/sign_cn.rst
    layers_cn/similarity_focus_cn.rst
    layers_cn/sin_cn.rst
    layers_cn/slice_cn.rst
    layers_cn/smooth_l1_cn.rst
    layers_cn/soft_relu_cn.rst
    layers_cn/softmax_cn.rst
    layers_cn/softmax_with_cross_entropy_cn.rst
    layers_cn/softplus_cn.rst
    layers_cn/softshrink_cn.rst
    layers_cn/softsign_cn.rst
    layers_cn/space_to_depth_cn.rst
    layers_cn/spectral_norm_cn.rst
    layers_cn/split_cn.rst
    layers_cn/sqrt_cn.rst
    layers_cn/square_cn.rst
    layers_cn/square_error_cost_cn.rst
    layers_cn/squeeze_cn.rst
    layers_cn/ssd_loss_cn.rst
    layers_cn/stack_cn.rst
    layers_cn/stanh_cn.rst
    layers_cn/StaticRNN_cn.rst
    layers_cn/strided_slice_cn.rst
    layers_cn/sum_cn.rst
    layers_cn/sums_cn.rst
    layers_cn/swish_cn.rst
    layers_cn/Switch_cn.rst
    layers_cn/tanh_cn.rst
    layers_cn/tanh_shrink_cn.rst
    layers_cn/target_assign_cn.rst
    layers_cn/teacher_student_sigmoid_loss_cn.rst
    layers_cn/temporal_shift_cn.rst
    layers_cn/tensor_array_to_tensor_cn.rst
    layers_cn/thresholded_relu_cn.rst
    layers_cn/topk_cn.rst
    layers_cn/transpose_cn.rst
    layers_cn/unfold_cn.rst
    layers_cn/Uniform_cn.rst
    layers_cn/uniform_random_cn.rst
    layers_cn/uniform_random_batch_size_like_cn.rst
    layers_cn/unique_cn.rst
    layers_cn/unique_with_counts_cn.rst
    layers_cn/unsqueeze_cn.rst
    layers_cn/unstack_cn.rst
    layers_cn/warpctc_cn.rst
    layers_cn/where_cn.rst
    layers_cn/While_cn.rst
    layers_cn/yolo_box_cn.rst
    layers_cn/yolov3_loss_cn.rst
    layers_cn/zeros_cn.rst
    layers_cn/zeros_like_cn.rst
