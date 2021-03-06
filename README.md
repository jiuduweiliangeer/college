基于Spring Boot的宿舍管理系统
已基本完成，主要实现的功能有
管理端：
    宿舍管理员：宿舍管理员具有管理本栋楼层所有学生的权限
       1.对非本栋人员进行进出登记，包括进出原因，进出时间，进出目的地
       2.对本栋已有学生进行管理，根据学生的姓名，性别，电话号码进行查询
       3.对每日缺勤学生进行上报，上报至学校管理员处
       4.处理学生提出的问题，例如设备报修等，如果有设备保修请求，显示为待处理，需要及时联系相关人员，后显示处理中，当学生确认已经解决之后，状态修改为完成
       5.对存在安全隐患的学生宿舍进行标记
       6.对于学生提出的建议进行筛选性回复，让宿舍更加和谐
       7.对新进校学生进行登记入册，对离校学生销号并进行登记
    学校管理员：学校管理员具有所有学生宿舍相关权限，也可以管理宿舍管理管理员相关信息
        1.对管理员人事进行管理，如解雇雇佣等
        2.对管理员上报的缺勤情况进行整理，进行处理
        3.查看学生的宿舍分布情况，对学生各种情况进行单独处理
学生端：
  1.查看相关同学（相同班级）宿舍情况（不得修改）
  2.对宿舍内物品损坏进行申报，等待处理
  3.每晚十一点半之前打卡，如果未打卡则记录为缺勤状态
  4.如确有重要事务需要当晚不在校住宿，提出请假申请，管理员报送给学校管理端，学校管理处允许即可当日不在校居住
  5.如有确切需求可提出更换宿舍申请，学校方面和相关人员同意后，可变更宿舍




