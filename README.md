# --test
虚拟敲除单基因/多基因同时敲除

# 敲除前数据处理seurat_obj <- FindVariableFeatures(object=seurat_obj, selection.method="vst", nfeatures=2000；
# nfeatures值会影响后续的分析结果 可以table(pbmc$Type)或是table(seurat_obj$Type)查看Tumor数量来确定nfeatures值，nfeatures值越大对性能要求越高，＞5000时一般要用服务器跑

