# 4-20
make elevation mapping more stable

# 4-21
start to store this project on github

# 4-22
在convex_plane_segmentation里边加入了normal

应该直接用elevation mapping里的,明天再思考一下

# 4-23
elevation_mapping里的traversibility是用在navigation里的
调整了plane segmentation里的标准差系数，现在更加稳定了

# 4-24
今天这边应该没改什么代码,debug的时候在SegmentedPlaneProjection.cpp里改了一下都不对就注释掉了

之后试试用elevation_mapping_raw里的traversibility来做navigation

# 5-7
目前是一个能用的版本，尝试解决多机通信时出现的TF_ERROR

# 5-15
按照力哥的意见修改系统时间后,TF_ERROR报错解决了

# 5-21
重新配环境，cuda12.0+cupy12X 解决了cp.int的报错。 运行的时候有一个error，明天解决

# 5-22
是因为之前在PlaneDecompositionPipeline.cpp中加了normal

