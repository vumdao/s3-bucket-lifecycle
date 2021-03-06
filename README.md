<p align="center">
  <a href="https://dev.to/vumdao">
    <img alt="How Is Your S3 Bucket Life-Cycle?" src="https://github.com/vumdao/s3-bucket-lifecycle/blob/master/cover.png?raw=true" width="500" />
  </a>
</p>
<h1 align="center">
  <div><b>How Is Your S3 Bucket Life-Cycle?</b></div>
</h1>

### - Set S3 bucket life-cycle rule is to save cost of long-term storage objects such database backup. This post gives an experinced case and a sumarized of S3 storage object class.

---

## What’s In This Document 
- [Example of S3 Life-cycle Rule](#-Example-of-S3-Life-cycle-Rule)
- [S3 Object Storage Classes](#-S3-Object-Storage-Classes)

---

### 🚀 **[Example of S3 Life-cycle Rule](#-Example-of-S3-Life-cycle-Rule)**
![Alt-Text](https://github.com/vumdao/s3-bucket-lifecycle/blob/master/lifecycle_rule.png?raw=true)

### 🚀 **[S3 Object Storage Classes](#-S3-Object-Storage-Classes)**
- Amazon S3 supports a waterfall model for transitioning between storage classes, as shown in the following diagram.
![Alt-Text](https://github.com/vumdao/s3-bucket-lifecycle/blob/master/lifecycle_waterfall.png?raw=true)

- Advanced knowledge here is about extend object classes which AWS uses for CloudWatch dimensions and you are charged for this additional storage 
![Alt-Text](https://github.com/vumdao/s3-bucket-lifecycle/blob/master/bucket_metrics.png?raw=true)

![Alt-Text](https://github.com/vumdao/s3-bucket-lifecycle/blob/master/glaicer_obj_overhead.png?raw=true)

![Alt-Text](https://github.com/vumdao/s3-bucket-lifecycle/blob/master/deep_archive_obj_overhead.png?raw=true)

- See cloudwatch metric graph to see AWS add more storage classes
![Alt-Text](https://github.com/vumdao/s3-bucket-lifecycle/blob/master/cloudwatch_metric_graph.png?raw=true)

<h3 align="center">
  <a href="https://dev.to/vumdao">:stars: Blog</a>
  <span> · </span>
  <a href="https://github.com/vumdao/">Github</a>
  <span> · </span>
  <a href="https://vumdao.hashnode.dev/">Web</a>
  <span> · </span>
  <a href="https://www.linkedin.com/in/vu-dao-9280ab43/">Linkedin</a>
  <span> · </span>
  <a href="https://www.linkedin.com/groups/12488649/">Group</a>
  <span> · </span>
  <a href="https://www.facebook.com/CloudOpz-104917804863956">Page</a>
  <span> · </span>
  <a href="https://twitter.com/VuDao81124667">Twitter :stars:</a>
</h3>