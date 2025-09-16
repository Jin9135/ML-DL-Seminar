## Data Research Code Version 1.1 ##
로그에 loss function 추가
Result에 loss function 명시

# 예시 #
losses = {
    "CE": make_loss("ce"),
    "GCE(q=0.7)": make_loss("gce", q=0.7),
    "Focal(g=2, α=0.25)": make_loss("focal", gamma=2.0, alpha=0.25),
    "CCE(c=3)": make_loss("cce", cap=3.0),
    "SCCE(c=3, β=1)": make_loss("scce", cap=3.0, beta=1.0),
}

for name, loss_fn in losses.items():
    model, hist, test_score = run_experiment(
        df_wine, "uci_wine",
        loss_name=name,
        loss_fn=loss_fn, epochs=50, batch_size=64, lr=1e-3, seed=43
    )
