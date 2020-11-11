## sort 空索引导致unmapped问题 

#### 解决办法, 加unmapped_type参数
  
    {
        "sort": [{"time": {"order": "desc", "unmapped_type": "date"}},]
    }
