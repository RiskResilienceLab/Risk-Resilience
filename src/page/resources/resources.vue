<template>
  <div class="page-container">
    <div class="section">
      <h3>共享资源</h3>

      <div class="content-wrapper">
        <div class="resource-list">
          <div class="resource-card">
            <div class="card-header">
              <div class="icon-box">
                <el-icon class="resource-icon"><Document /></el-icon>
              </div>
              <div class="header-text">
                <h4>Storm surge tidal water level data for 23 coastal regions in China</h4>
                <p class="resource-type">代码与数据资源</p>
              </div>
            </div>

            <div class="card-body">
              <p class="resource-desc">
                本文相关的代码与数据已上传至 Figshare，可通过下方链接访问。
              </p>

              <div class="resource-meta">
                <p>
                  <strong>资源链接：</strong>
                  <a
                      href="https://figshare.com/articles/dataset/Storm_surge_tidal_water_level_data_for_23_coastal_regions_in_China/29925842"
                      target="_blank"
                      rel="noopener noreferrer"
                  >
                    https://figshare.com/articles/dataset/Storm_surge_tidal_water_level_data_for_23_coastal_regions_in_China/29925842
                  </a>
                </p>

                <p>
                  <strong>对应论文：</strong>
                  <span class="citation">
                    <span class="author">Fang, J.*</span>, Huang, J., Bian, W. et al. (2026).
                    Reconstruction of Extreme Sea Levels in coastal China using Multiple Deep Learning models.
                    <em>Scientific Data</em>.
                    <a
                        href="https://doi.org/10.1038/s41597-026-06593-w"
                        target="_blank"
                        rel="noopener noreferrer"
                    >
                      https://doi.org/10.1038/s41597-026-06593-w
                    </a>
                  </span>
                </p>
              </div>

              <div class="tag-list">
                <span class="tag">Figshare</span>
                <span class="tag">Data</span>
                <span class="tag">Code</span>
                <span class="tag">Scientific Data</span>
              </div>

              <div class="action-group">
                <a
                    class="action-btn primary"
                    href="https://figshare.com/articles/dataset/Storm_surge_tidal_water_level_data_for_23_coastal_regions_in_China/29925842"
                    target="_blank"
                    rel="noopener noreferrer"
                >
                  <el-icon><Link /></el-icon>
                  访问资源
                </a>

                <a
                    class="action-btn"
                    href="https://doi.org/10.1038/s41597-026-06593-w"
                    target="_blank"
                    rel="noopener noreferrer"
                >
                  <el-icon><Reading /></el-icon>
                  查看论文
                </a>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script setup>
import { Document, Link, Reading } from '@element-plus/icons-vue'
</script>

<style scoped>
.page-container {
  padding: 1.25rem;
  width: 70%;
  margin-left: 20%;
  box-sizing: border-box;
}

.section {
  margin-bottom: 30px;
}

h3 {
  font-size: 20px;
  color: #333;
  margin-bottom: 20px;
  padding-bottom: 10px;
  border-bottom: 2px solid #efecec;
}

.content-wrapper {
  background-color: #fff;
  border-radius: 8px;
  box-shadow: 0 2px 12px rgba(0, 0, 0, 0.03);
  padding: 20px;
}

.resource-list {
  display: flex;
  flex-direction: column;
  gap: 20px;
}

.resource-card {
  background: #fff;
  border: 1px solid #ebeef5;
  border-radius: 12px;
  padding: 24px;
  transition: all 0.3s ease;
}

.resource-card:hover {
  box-shadow: 0 6px 18px rgba(0, 0, 0, 0.06);
  border-color: #dcdfe6;
}

.card-header {
  display: flex;
  align-items: center;
  gap: 16px;
  margin-bottom: 18px;
}

.icon-box {
  width: 56px;
  height: 56px;
  border-radius: 12px;
  background: #f4f8ff;
  display: flex;
  align-items: center;
  justify-content: center;
  flex-shrink: 0;
}

.resource-icon {
  font-size: 28px;
  color: #409eff;
}

.header-text h4 {
  margin: 0 0 6px 0;
  font-size: 18px;
  color: #303133;
  line-height: 1.5;
}

.resource-type {
  margin: 0;
  color: #909399;
  font-size: 14px;
}

.card-body {
  color: #606266;
  line-height: 1.8;
}

.resource-desc {
  margin: 0 0 16px 0;
  font-size: 15px;
}

.resource-meta p {
  margin: 0 0 12px 0;
  word-break: break-word;
}

.resource-meta strong {
  color: #303133;
}

.resource-meta a {
  color: #409eff;
  text-decoration: none;
}

.resource-meta a:hover {
  text-decoration: underline;
}

.citation {
  color: #606266;
}

.author {
  font-weight: 700;
}

.tag-list {
  display: flex;
  flex-wrap: wrap;
  gap: 10px;
  margin: 18px 0 22px;
}

.tag {
  display: inline-block;
  padding: 4px 12px;
  font-size: 13px;
  color: #409eff;
  background: #ecf5ff;
  border: 1px solid #d9ecff;
  border-radius: 999px;
}

.action-group {
  display: flex;
  flex-wrap: wrap;
  gap: 12px;
}

.action-btn {
  display: inline-flex;
  align-items: center;
  gap: 6px;
  padding: 10px 16px;
  border-radius: 8px;
  text-decoration: none;
  font-size: 14px;
  color: #606266;
  background: #f5f7fa;
  border: 1px solid #dcdfe6;
  transition: all 0.3s ease;
}

.action-btn:hover {
  color: #409eff;
  border-color: #b3d8ff;
  background: #ecf5ff;
}

.action-btn.primary {
  color: #fff;
  background: #409eff;
  border-color: #409eff;
}

.action-btn.primary:hover {
  background: #66b1ff;
  border-color: #66b1ff;
  color: #fff;
}

@media (max-width: 768px) {
  .page-container {
    width: 90%;
    margin: 1rem auto;
    padding: 1rem;
  }

  .content-wrapper {
    padding: 16px;
  }

  .resource-card {
    padding: 18px;
  }

  .card-header {
    align-items: flex-start;
  }

  .icon-box {
    width: 48px;
    height: 48px;
  }

  .resource-icon {
    font-size: 24px;
  }

  .header-text h4 {
    font-size: 16px;
  }

  .resource-desc,
  .resource-meta p {
    font-size: 14px;
  }

  .action-group {
    flex-direction: column;
  }

  .action-btn {
    justify-content: center;
    width: 100%;
  }
}
</style>