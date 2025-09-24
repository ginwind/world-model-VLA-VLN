VLA-WM:

DREMA：构建了一个可交互的物理世界模型，结合高保真的高斯渲染与物理引擎，支持在想象空间中执行动作并验证其后果，实现闭环的模仿学习。
GWM：提出基于高斯Splatting的3D世界模型，支持action-conditioned的多步rollout，可用于在线强化学习与策略优化。
LaDi-WM：在latent空间中进行状态预测，并通过世界模型和动作策略的迭代过程实现策略的逐步优化，体现了闭环的动作修正机制。
ParticleFormer：基于点云的Transformer世界模型，结合MPC进行在线控制，策略每一步都依赖于世界模型的反馈预测。
Object-Centric World Model：采用slot-based表示进行对象级预测，支持语言引导的多步状态生成，策略可在预测空间中进行规划与调整。
-insight：闭环方法的优势在于其更强的泛化能力和在线适应性，尤其在面对非结构化环境任务、复杂物理交互或长时序规划时表现更优。然而，这类方法通常训练成本更高，需要的反应频率更快，系统设计更复杂，对世界模型的准确性和稳定性要求也更高。


MindJourney Test-Time Scaling with World Models for Spatial Reasoning
